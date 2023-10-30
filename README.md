{
 "cells": [
  {
   "cell_type": "raw",
   "id": "647ad17b",
   "metadata": {},
   "source": []
  },
  {
   "cell_type": "markdown",
   "id": "8ee8d697",
   "metadata": {},
   "source": [
    "# Tugas Computer Vision - Arithmetic Operations\n",
    "\n",
    "## Pertama-tama, ganti NIM di nama file ini. Klik <font color=\"red\">File -> Save as... </font>\n",
    "\n",
    "Lalu isi yang di bawah ini. Untuk mengedit cell ini, double-click di sini.\n",
    "### NAMA: ....\n",
    "### NIM: ...\n",
    "\n",
    "Video kuliah terkait topik ini: https://www.youtube.com/watch?v=W5FyJ-cavAU\n",
    "\n",
    "\n",
    "#### Lengkapi kode di bawah dan jalankan\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "95237220",
   "metadata": {},
   "outputs": [],
   "source": [
    "from time import ctime\n",
    "from os import getcwd\n",
    "import sys\n",
    "nama = \"NAMA SAYA\"     ## Ganti dengan namamu\n",
    "NIM = \"A710250999\"     ## Ganti dengan NIM-mu\n",
    "kota = \"Surakarta\"     ## Ganti dengan kotamu\n",
    "print(\"NAMA:\", nama)\n",
    "print(\"NIM :\", NIM)\n",
    "print(\"Kota:\", kota)\n",
    "print(ctime())\n",
    "print(\"\")\n",
    "print(getcwd())\n",
    "print(sys.executable)\n",
    "print(sys.version)"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "89b763ab",
   "metadata": {},
   "source": [
    "##  Import the libraries"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "5dcf81cc",
   "metadata": {},
   "outputs": [],
   "source": [
    "## Silakan import semua library yang diperlukan di cell ini\n",
    "# ..."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "4cc3d3b9",
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "markdown",
   "id": "2e699057",
   "metadata": {},
   "source": [
    "## Buatlah blending tiga gambar yang disediakan.\n",
    "\n",
    "- Gambar pertama adalah gedung edutorium ums. Ini adalah gambar utama.\n",
    "- Gambar kedua adalah tulisan \"pti-ums-2023\"\n",
    "- Gambar ketiga adalah logo PTI UMS\n",
    "\n",
    "Campur (*blend*) ketiga gambar di atas dengan ketentuan:\n",
    "- Gambar pertama bobot 1\n",
    "- Gambar kedua bobot 0.3, tulisan kuning akan terlihat samar. \n",
    "  - Ketentuan letak: pojok tulisan kiri atas bergabung di pixel (50, 50) gambar utama - seperti di video kuliah, dan berakhir 50 pixel dari kanan. Tulisan akan tampak simetris di tengah-atas. Jadi kamu harus menyesuaikan ukurannya. Saat penyesuaian ukuran, aspect ratio tidak boleh berubah.\n",
    "- Gambar ketiga bobot 0.5, logo PTI akan terlihat samar tapi lebih jelas\n",
    "  - Perhatikan bahwa gambar logonya latar belakang aslinya adalah putih (255 atau kurang sedikit). Sebelum blending, kamu perlu merubah latar belakangnya menjadi hitam (bernilai 0). **Lakukan ini dengan cv2**\n",
    "  - Ketentuan letak: pojok kiri bawah logo berimpitan dengan pixel 20 dari bawah dan 20 dari kiri gambar utama. Tinggi logo tidak boleh melebihi garis separuh gambar utama. Kamu harus menyesuaikan ukurannya. Saat penyesuaian ukuran, aspect ratio tidak boleh berubah.\n",
    "\n"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "d2fa60fa",
   "metadata": {},
   "outputs": [],
   "source": [
    "from IPython.display import Markdown\n",
    "Markdown('<br><font size=\"7\">{}...{}</font>'.format(chr(128552), chr(128557) ) )"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "886b323b",
   "metadata": {},
   "outputs": [],
   "source": [
    "Markdown('<br><font size=\"7\">{}</font>'.format(chr(128512)))"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "d58d1513",
   "metadata": {},
   "outputs": [],
   "source": [
    "## Taruh kodemu di bawah ini. Beri komentar selengkap lengkapnya\n",
    "# ..."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "4f16c04d",
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "870ab4ab",
   "metadata": {},
   "outputs": [],
   "source": []
  },
  {
   "cell_type": "markdown",
   "id": "bec61693",
   "metadata": {},
   "source": [
    "**Pertanyaan:** untuk logo PTI, mengapa kita perlu merubah latar belakangnya menjadi hitam? Apa akibatnya kalau langkah ini tidak dilakukan? (Kamu bisa bereksperimen)\n",
    "\n",
    "**Jawaban:** ...."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "02616ef1",
   "metadata": {},
   "outputs": [],
   "source": [
    "Markdown('<br><font size=\"7\">{}</font>'.format(chr(129300)))"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "bdaa25e6",
   "metadata": {},
   "source": [
    "### Save, add, commit. Then push to github"
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "54cc289c",
   "metadata": {},
   "outputs": [],
   "source": [
    "Markdown('<br><font size=\"7\">{}</font>'.format(chr(128515)))"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.11.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}

