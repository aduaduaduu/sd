#  installasi free sd linux (debian)
1. Download GFPGANv1.4.pth
2. Download sd-v1-4.ckpt
3. Clone disembarang folder "git clone https://github.com/AUTOMATIC1111/stable-diffusion-webui"
4. Masuk dir "/stable-diffusion-webui/"
5. Create venv menggunakan python3.10
6. Aktifkan venv
7. Update pip ke versi terbaru menggunakan python3.10
8. Copy file GFPGANv1.4.pth ke dalam dir "/stable-diffusion-webui/"
9. Copy file sd-v1-4.ckpt ke dalam dir "/stable-diffusion-webui/models/Stable-diffusion/"
10. Jalankan webui.sh menggunakan bash
11. Setelah installasi selesai jalankan di dalam web browser sesuai dengan port yang disediakan
12. Setelah berhasil dijalankan di dalam browser, close browser lalu stop webui.sh yang sedang berjalan di dalam terminal
13. Masuk dir "/stable-diffusion-webui/repositories"
14. Clone "git clone https://github.com/facebookresearch/xformers.git" di dalam dir "/stable-diffusion-webui/repositories/"
15. Masuk dir "/stable-diffusion-webui/repositories/xformers"
16. Update dengan repos terbaru "git submodule update --init --recursive"
17. Install setup requirments yang diperlukan "pip install -r requirements.txt"
18. Install "pip install -e ." (prosesnya sekitar 20-30 menitan. Tidak ada log sama sekali tapi gapapa, ditunggu saja sampe selesai instalasinya)
