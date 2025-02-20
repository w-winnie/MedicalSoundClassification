DATA
https://www.kaggle.com/competitions/airs-ai-in-respiratory-sounds/overview
kaggle competitions download -c airs-ai-in-respiratory-sounds

ENV
conda create -n med_sound_venv python=3.10
conda activate med_sound_venv
pip install -r requirements.txt

COMMIT 
git checkout develop
pip freeze > requirements.txt
git add .
git commit -m "commit message"
git push origin develop