
<div align="center">
<a href="https://taruma.github.io/hidrokit"><img src="https://taruma.github.io/hidrokit/assets/images/presskit/hidrokit-800x200.jpg" alt="logo hidrokit"></a><br>

![PyPI - Python Version](https://img.shields.io/pypi/pyversions/hidrokit.svg)
[![GitHub license](https://img.shields.io/github/license/taruma/hidrokit.svg)](https://github.com/taruma/hidrokit/blob/master/LICENSE)

<a href="https://taruma.github.io/hidrokit"><b>Kunjungi situs resmi hidrokit.</b></a>
</div>

`hidrokit` adalah proyek _open source_ paket *python* yang dapat digunakan untuk membantu proses analisis hidrologi dimulai dari pengolahan data, analisis data, dan visualisasi data.

## Release

<table>
  <tr align="center">
    <th>Release</th>
    <th>PyPI</th>
    <th>Github</th>
    <th>Github (Pre-release)</th>
  </tr>
  <tr>
    <td></td>
    <td><img alt="PyPI" src="https://img.shields.io/pypi/v/hidrokit.svg?logo=pypi"></td>
    <td><img alt="GitHub release" src="https://img.shields.io/github/release/taruma/hidrokit.svg?logo=github"></td>
    <td><img alt="GitHub release" src="https://img.shields.io/github/release-pre/taruma/hidrokit.svg?logo=github"></td>
  </tr>
</table>


## Status

<table>
  <tr align="center">
    <th>Branch</th>
    <th>master</th>
    <th>latest</th>
    <th>gh-pages</th>
  </tr>
  <tr>
    <td><b>Services</b></td>
    <td></td>
    <td></td>
    <td></td>
  </tr>
  <tr>
    <td>Travis-ci</td>
    <td><img alt="master" src="https://img.shields.io/travis/taruma/hidrokit/master.svg?label=build&logo=travis"></td>
    <td><img alt="latest" src="https://img.shields.io/travis/taruma/hidrokit/latest.svg?label=build&logo=travis"></td>
    <td><img alt="gh-pages" src="https://img.shields.io/travis/taruma/hidrokit/gh-pages.svg?label=build&logo=travis"></td>
  </tr>
  <tr>
    <td>Codecov</td>
    <td><img alt="master" src="https://img.shields.io/codecov/c/github/taruma/hidrokit/master.svg?logo=codecov"></td>
    <td><img alt="latest" src="https://img.shields.io/codecov/c/github/taruma/hidrokit/latest.svg?logo=codecov"></td>
    <td></td>
  </tr>
  <tr>
    <td>Codacy</td>
    <td><img alt="master" src="https://img.shields.io/codacy/grade/4e7531e009dc49d682b4e1049be7971c/master.svg?logo=codacy"></td>
    <td><img alt="Codacy branch grade" src="https://img.shields.io/codacy/grade/4e7531e009dc49d682b4e1049be7971c/latest.svg?logo=codacy"></td>
    <td></td>
  </tr>
</table>

## Memulai

Untuk memudahkan penggunaan, disarankan menggunakan **Anaconda3** sebagai distribusi *python*. Download **Anaconda3** [disini](https://www.anaconda.com/download/).

## Instalasi / Pemasangan

`hidrokit` didistribusikan melalui [PyPI](https://pypi.org/). Pemasangan dilakukan dengan perintah pada _(Anaconda) command prompt_:

```bash
pip install hidrokit
```
*(akses internet diperlukan saat melakukan pemasangan)*

### Versi terbaru (_unstable_/_latest_)

Untuk versi bisa melakukan pemasangan berdasarkan cabang _latest_.
```bash
pip install -e git+https://github.com/taruma/hidrokit.git@latest
```

## Catatan penting
- hidrokit hanya mendukung python versi 3.6 ke atas.
- Instalasi `xlrd` dibutuhkan jika menggunakan module `excel` untuk membaca bilah _Excel_.
- Versi 0.2.0 tidak memiliki *backward-compatibility* dengan versi 0.1.x.

## Penggunaan

Untuk memulai penggunaan, gunakan perintah `import`. Contoh:

```python
from hidrokit.prep import read
from hidrokit.prep.read import missing_row
from hidrokit.viz import graph
```

Untuk contoh penggunaan baca bagian [_notebook_](#hidrokit-notebook).

## Hidrokit Notebook

Kumpulan contoh _notebook_ dapat diakses di halaman [Hidrokit Notebook](https://taruma.github.io/hidrokit-nb/).

<div align="center">
<a href="https://taruma.github.io/hidrokit-nb"><img src="https://taruma.github.io/hidrokit-nb/assets/images/hidrokit-nb-800x200.jpg" width="50%"></a>
</div>

## Untuk Kontributor

Tertarik menjadi kontributor? Baca [**berkontribusi**](https://github.com/taruma/hidrokit/wiki/Berkontribusi) untuk kode etik, melakukan _pull request_, dan penjelasan lebih rinci hal lainnya. Proyek _open-source_ ini terbuka untuk siapa saja dengan berbagai latar belakang.
