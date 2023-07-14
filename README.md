# Django-MyTask
Belajar membuat aplikasi dafter tugas menggunakan Django versi 4.2


## Bagian 0: SETUP
        
        Tujuan:

        1. Membuat remote repositori
        2. Meng-klone repositori sebagai root proyek

        Lankah-lankah:

        1. Membuat akun pada Github
        2. Menginstal Git
        3. Membuat konfigursasi Git
        4. Membuat ssh-key lokal
        5. Membuat ssh-key di Github
        6. Membuat repositori baru pada Github
        7. Meng-klon repositori
        8. Menginstal Sublime Text editor
        9. Membuka file proyek pada Sublime Text

        modified:   README.md
        

## Bagian 2: Membuat Proyek Django
        
        Tujuan:

        1. Membuat Proyek Django
        2. Menjalankan server untuk kali pertama dan melihat 
           default proyek django di browser


#### 2.1 Membuat lingkungan virtual 

        Tujuan:

        1. Membuat lingkungan vituala yang terisolasi

        Langkah-langkah:

        1. Menginstal Python versi 3++
        2. Memastikan versi Python yang tersinsal
        2. Memastikan versi pip

        Kode perintah:

        hp@ING:MyTask ~ python -V << -- memastikan versi python
        Python 3.9.5

        hp@ING:MyTask ~ pip -V << -- memastikan versi pip
        pip 23.1.2 from C:\python\Python39\lib\site-packages\pip (python 3.9)

        hp@ING:MyTask ~ python -m venv venv3942 --promp mytask << -- membuat lingkungan virtual


        File baru/modifikasi:

        modified:   .gitignore
        modified:   README.md


#### 2.2 Menginstal Django versi 4.2

        Tujuan:

        1. Menginstal Django versi 4.2

        Langkah-langkah:

        1. Mengaktifkan lingkungan virtual (venv3942)
        2. Menginstal Django versi 4.2
        2. Meng-upgrade pip

        Kode perintah:

        hp@ING:MyTask ~ venv3942\Scripts\activate << -- mengaktifkan lingkungan virtual

        (mytask) hp@ING:MyTask ~ pip install django==4.2 << -- menginstal django
        Collecting django==4.2
        ....
        WARNING: You are using pip version 21.1.1; however, version 23.1.2 is available.
        You should consider upgrading via the 'c:\users\hp\desktop\django-mytask\venv3942\scripts\python.exe -m pip install --upgrade pip' command.

        (mytask) hp@ING:MyTask ~ python.exe -m pip install --upgrade pip
        ...
        Successfully installed pip-23.1.2


        File baru/modifikasi:

        modified:   README.md


#### 2.3 Membuat Proyek Django dengan nama mytask

        Tujuan:

        1. Membuat proyek django dengan nama 'mytask'

        Langkah-langkah:

        1. Memastikan lingkungan virtual diaktifkan
        2. Memeriksa versi django
        3. Membuat proyek django dengan nama 'mytask'
        4. Memeriks hasil perintah
        5. Memodifikasi struktur file


        Kode perintah:

        (mytask) hp@ING:MyTask ~ << --- 1. Memastikan lingkungan virtual diaktifkan
        (mytask) hp@ING:MyTask ~ pip list << --- 2. Memeriksa versi django
        Package           Version
        ----------------- -------
        asgiref           3.7.2
        Django            4.2
        pip               23.1.2
        setuptools        56.0.0
        sqlparse          0.4.4
        typing_extensions 4.7.1
        tzdata            2023.3

        (mytask) hp@ING:MyTask ~ django-admin startproject mytask << --- 3. Membuat proyek django dengan nama 'mytask'

        (mytask) hp@ING:MyTask ~ ls << --- 4. Memeriks hasil perintah
        README.md  _docs  mytask  venv3942


        File baru/modifikasi (lama):

        modified:   README.md
        new file:   mytask/manage.py
        new file:   mytask/mytask/__init__.py
        new file:   mytask/mytask/asgi.py
        new file:   mytask/mytask/settings.py
        new file:   mytask/mytask/urls.py
        new file:   mytask/mytask/wsgi.py

        File baru/modifikasi (baru):

        modified:   README.md
        new file:   manage.py
        new file:   mytask/__init__.py
        new file:   mytask/asgi.py
        new file:   mytask/settings.py
        new file:   mytask/urls.py
        new file:   mytask/wsgi.py












