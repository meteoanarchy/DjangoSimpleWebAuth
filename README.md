# Django Simple Web Authentication

Saya sarankan pakai distribusi Anaconda di sini, soalnya saya kan buat <i>web developer</i> utamanya pakai Python buat riset jadi ya pakai [Anaconda](https://www.anaconda.com/distribution/) aja. Oh ya, <i>by the way</i>, karena saya orang kiri jadi proses instalasi nya hanya buat GNU/Linux :trollface:.

Jalankan perintah kayak gini di Terminal:

* Bikin virtualenv:  ```conda create --name webauthsim python=3.6 django=2```

* Aktifkan virtualenv: ```source activate webauthsim```

* Buat memastikan ketik: ```pip freeze```

* Mustinya muncul kayak gini:
```
certifi==2018.11.29
Django==2.1.4
pytz==2019.1
```

* Mulai project: ```django-admin.py startproject webauthsim .```


* Untuk menonaktifkan virtualenv: ```source deactivate```
