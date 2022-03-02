ini adalah perintah bawaan untuk membersihkan file yang tidak terlacak. Ini bisa termasuk menghapus artefak build sementara atau menggabungkan file konflik.
Jika Anda juga ingin menghapus direktori, jalankan git clean -f -d
git branch <nama_branch>
Dalam strategi penggabungan yang paling umum digunakan ini, sejarah hanyalah satu garis lurus. Saat Anda membuat cabang, buat beberapa komit di cabang itu, saat Anda siap untuk menggabungkan, tidak ada penggabungan baru di master. Dengan begitu penunjuk master hanya bergerak lurus ke depan dan sejarah adalah satu garis lurus. Dalam penggabungan Rekursif, setelah Anda bercabang dan membuat beberapa komit, ada beberapa komit asli baru di 'master'. Jadi, ketika saatnya untuk menggabungkan, git berulang di atas cabang dan membuat komit gabungan baru. Komit gabungan terus memiliki dua orang tua.
git checkout <nama_branch>
rm <nama_file>
git branch -d <nama_branch>
Perintah git diff akan membandingkan perubahan yang baru saja dilakukan dengan revisi/commit terakhir pada repository.
git reset HEAD <nama_file>
dengan menggabungkan branch master dengan branch lain yang sudah di edit isi nya sebelumnya agar tidak terjadi konflik