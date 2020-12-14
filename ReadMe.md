The goal of this project is to protect against malicious URLs, particularly adversarial attacks. It's been identified that a competent adversarial URL generating system can come up with URLs that can get past ML classifiers  at the rate of one every 20 seconds or so. This makes current malicious URL detection systems insufficient. 

We overcome this using a Random Forest Classifier with adversarial training to counter adversarial attacks that works with an accuracy of approx. 94 percent and a false positive rate of approximately 3.7 percent. 

Although this project isn't directly a standout performer since several other adversarially trained models work just as good as this one with around 2 percent increase in the false positive rate, as without adversarial training. In any case, such an increase in the false positive rate is not acceptable, and subsequently the model should be improved upon in that aspect.
