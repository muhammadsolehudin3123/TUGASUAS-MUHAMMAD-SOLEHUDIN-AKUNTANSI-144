# BERIKUT ADALAH KODE PYTHON UNTUK TUGAS BERIKUT YANG TERHUBUNG KE FILE JENIS CSV

import pandas as pd
import matplotlib.pyplot as plt
from sklearn.cluster import KMeans

# Membaca data dari file CSV dengan delimiter titik koma
df = pd.read_csv('data.csv', delimiter=';')

# Menampilkan beberapa baris pertama data
print("Data awal:")
print(df.head())

# Menampilkan ringkasan statistik data
print("\nRingkasan statistik:")
print(df.describe())

# Menampilkan distribusi usia (Histogram)
plt.figure(figsize=(10, 6))
plt.hist(df['Usia'], bins=10, edgecolor='black', color='skyblue')
plt.title('Distribusi Usia')
plt.xlabel('Usia')
plt.ylabel('Frekuensi')
plt.grid(True)
plt.show()

# Menampilkan jumlah orang per kota (Bar Chart)
plt.figure(figsize=(10, 6))
colors = plt.cm.tab20.colors  # Menggunakan colormap tab20 untuk warna yang bervariasi
df['Kota'].value_counts().plot(kind='bar', color=colors, edgecolor='black')
plt.title('Jumlah Orang per Kota')
plt.xlabel('Kota')
plt.ylabel('Jumlah Orang')
plt.xticks(rotation=45)
plt.grid(True)
plt.show()

# Kluster menggunakan KMeans
kmeans = KMeans(n_clusters=3, random_state=0)  # Kita akan membuat 3 kluster sebagai contoh
df['Cluster'] = kmeans.fit_predict(df[['Usia']])

# Plot kluster
plt.figure(figsize=(10, 6))
colors = ['red', 'green', 'blue']
for cluster in range(3):
    clustered_data = df[df['Cluster'] == cluster]
    plt.scatter(clustered_data['Usia'], [cluster] * len(clustered_data), color=colors[cluster], label=f'Cluster {cluster}')
plt.title('Kluster Usia')
plt.xlabel('Usia')
plt.ylabel('Kluster')
plt.legend()
plt.grid(True)
plt.show()

# Menampilkan box plot untuk usia
plt.figure(figsize=(10, 6))
plt.boxplot(df['Usia'], vert=False, patch_artist=True, boxprops=dict(facecolor='skyblue', color='black'))
plt.title('Box Plot Usia')
plt.xlabel('Usia')
plt.grid(True)
plt.show()
