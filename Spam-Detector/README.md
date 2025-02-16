# AAS SPAM Detector

The objective is to develop a SPAM classifier capable of reaching at least 70% accuracy. You can, and should, use all that was presented in the theoretical notebooks.

The dataset is different from the toy one used in the class, instead the work will be done on the Enron SPAM dataset. The Enron-Spam dataset is a fantastic ressource collected by V. Metsis, I. Androutsopoulos and G. Paliouras and described in their publication ["Spam Filtering with Naive Bayes - Which Naive Bayes?"](https://nes.aueb.gr/ipl/nlp/pubs/ceas2006_paper.pdf). The dataset contains a total of 17.171 spam and 16.545 non-spam ("ham") e-mail messages (33.716 e-mails total). The original dataset and documentation can be found [here](http://www2.aueb.gr/users/ion/data/enron-spam/readme.txt).

## Setup

Follow the instructions bellow:
```bash
python3 -m venv venv
sourve venv/bin/activate
pip install -r requirements.txt
```

## Authors

* **Mário Antunes** - [mariolpantunes](https://github.com/mariolpantunes)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details