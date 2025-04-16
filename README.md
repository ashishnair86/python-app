sudo mysql -u root -p
apt install python3.10-venv
python3 -m venv myenv
source myenv/bin/activate  # Activate the virtual environment
pip install Flask Flask-MySQL mysql-connector-python
mkdir -p to-do-list/{static,templates,venv} && touch to-do-list/{app.py,requirements.txt,README.md}
source myenv/bin/activate
python app.py

