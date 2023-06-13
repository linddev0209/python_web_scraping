# You Need To Install PyQt5(REQUIRED)
pip install PyQt5

# Not Necessary
pip install PySide
pyuic5 -x [NAME_OF_UI_FILE].ui -o [NAME_OF_PY_FILE].py		(e.g. pyuic5 -x BradScraper.ui -o main.py)
python -m PyQt5.uic.pyuic -x [FILENAME].ui -o [FILENAME].py	(e.g. python -m PyQt5.uic.pyuic -x BradScraper.ui -o main.py)
