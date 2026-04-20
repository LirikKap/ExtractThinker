Грамотная установка пакетов. Иначе - конфликтуют extract_thinker и python-magic-bin

python -m venv venv
venv\Scripts\activate
python -m pip install --upgrade pip
python -m pip install python-magic-bin
python -m pip install extract_thinker
python -m pip install --force-reinstall python-magic-bin  # переустановка, чтобы перебить python-magic
python -m pip install python-dotenv
