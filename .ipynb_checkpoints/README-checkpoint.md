DATA <br>
https://www.kaggle.com/competitions/airs-ai-in-respiratory-sounds/overview <br>
kaggle competitions download -c airs-ai-in-respiratory-sounds <br>
<br>

ENV <br>
conda create -n med_sound_venv python=3.10 <br>
conda activate med_sound_venv <br>
pip install -r requirements.txt <br>
<br>

COMMIT <br>
git checkout develop <br>
pip freeze > requirements.txt <br>
git add . <br>
git commit -m "commit message" <br>
git push origin develop <br>
<br>

FILE STRUCTURE <br>
tree -L 3 
.
├── MedicalSoundClassification
│   ├── README.md
│   └── sandbox.ipynb
├── airs-ai-in-respiratory-sounds.zip
└── unzipped_folder
    ├── sounds
    │   └── sounds
    ├── test.csv
    └── train.csv

4 directories, 5 files

<br>