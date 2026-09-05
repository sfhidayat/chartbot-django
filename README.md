1. Terima prompt
        ↓
2. Simpan prompt → MySQL
        ↓
3. Kirim prompt → Ollama
        ↓
4. gemma 3:26b berpikir
        ↓
5. Jawaban kembali → Django
        ↓
6. Simpan jawaban → MySQL
        ↓
7. Tampilkan di browser

8. C:\localchat
│
├── venv
│
├── manage.py
│
├── config
│   ├── settings.py
│   ├── urls.py
│   └── ...
│
├── chat
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── forms.py
│   └── ...
│
├── templates
│   └── chat
│       └── chat.html
│
└── static
    ├── css
    └── js
