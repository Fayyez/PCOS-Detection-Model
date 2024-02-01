# What is PCOS?
According to [WHO](https://www.who.int/news-room/fact-sheets/detail/polycystic-ovary-syndrome), **Polycystic Ovary Syndrome (PCOS)** is a common hormonal condition that affects women of reproductive age. It usually starts during adolescence, but symptoms may fluctuate over time.

PCOS can cause hormonal imbalances, irregular periods, excess androgen levels and cysts in the ovaries. Irregular periods, usually with a lack of ovulation, can make it difficult to become pregnant. PCOS is a leading cause of infertility.

The condition affects an estimated **8–13%** of women of reproductive age, and up to **70%** of cases are undiagnosed. PCOS prevails in South Asian women, **especially in Pakistani women**, is **52%** as compared to white population with 20 - 25% in UK ([NIH, 2020](https://pubmed.ncbi.nlm.nih.gov/32580859/)), around **2-folds more** than worldwide reports.

### Purpose
To address the issue of undiagnosed cases issue, we have created a classification model. This model aims to improve the accuracy of PCOS diagnosis while making it more cost-effective. By considering various factors like blood tests, menstrual cycles, lifestyle, age etc, the model seeks to revolutionize how we identify PCOS, ultimately benefiting those affected by this condition.

### Dataset

We have used the [PCOS Dataset](https://www.kaggle.com/datasets/prasoonkottarathil/polycystic-ovary-syndrome-pcos) authored by [Prasoon Kottarathil](https://www.kaggle.com/prasoonkottarathil) at [Kaggle Datasets](https://www.kaggle.com/datasets/) for the model. (Visit the gievn links for more details). The dataset contains 43 physical and clinical parameters to determine PCOS and infertility related issues collected from 10 different hospitals across Kerala, India on a set of 541 samples of fertile female patients. The data was split in 80-20 ratio for training and testing.

## Models Used
Several diiferent models were used including the `RandomForestClassifier()`, `KNeighborsClassifier()`,  `AdaBoostClassifier()` and `XGBClassifier()` etc as welll as the `StackingClassifier()` using `RandomForestClassifier()` as the default meta model with promising results.

## License
This PCOS detection model is open-source software licensed under the GNU Lesser General Public License (LGPL) Version 2.1. See the LICENSE file for more details.
