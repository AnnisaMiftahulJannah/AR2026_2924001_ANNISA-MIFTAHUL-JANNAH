# PRAKTIKUM 02 - Diorama# di Unity 
## Identitas 
Nama  : Annisa Miftahul Jannah
NIM   : 2924001
 Kelas : IF 5A 
 ## Tujuan Menjelaskan tujuan praktikum secara singkat.
 Praktik pembuatan diorama bertujuan untuk memvisualisasikan konsep abstrak—seperti peristiwa sejarah, ekosistem, atau tata ruang—menjadi bentuk miniatur 3D yang nyata dan mudah dipahami. Selain memperkuat pemahaman materi melalui pengalaman belajar langsung (hands-on), praktik ini juga melatih kreativitas, keterampilan motorik halus, serta kepekaan terhadap skala dan proporsi ruang.

 ## Langkah Utama 
1.Buat  Assets/Scenes/Pertemuan02_Diorama.unity
2.Buat Ground dan objek lainnya
3.Susun komposisi
4. Buat Material
5. Atur lighting
6. Tambah Physics
7. Buat Prefab
8. Rapikan Hierarchy
9. Play Test

 ## Hasil Jelaskan fitur yang berhasil dibuat. 
Semua objek saat di Play Test sudah dapat bergerak
 ## Source Code Utama Nama file: RotateObject.cs 
using UnityEngine;
public class RotateObject : MonoBehaviour
{
    public float speed = 50f;
    void Update()
    {
        transform.Rotate(0f, speed * Time.deltaTime, 0f);
    }
}
 ## Bukti ![Hasil Praktikum](diorama.png) 
 ## Pengujian Status: BERHASIL 
 ## Kendala dan Solusi
Tidak ada.
 ## Kesimpulan
Praktikum ini berhasil mengimplementasikan pembuatan diorama 3D di Unity dengan menyusun berbagai objek, material, pencahayaan, dan komponen physics ke dalam struktur Hierarchy yang rapi. Penggunaan skrip RotateObject.cs memberikan unsur dinamis sehingga objek dapat bergerak saat Play Test. Dalam konteks Augmented Reality (AR), kemampuan menyusun diorama yang optimal dari segi skala, proporsi, dan performa (menggunakan Prefab) sangat krusial agar objek 3D dapat diproyeksikan ke dunia nyata secara realistis dan interaktif.