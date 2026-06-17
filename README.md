# Model Comparison and Tuning Using Australian Statlog 
## Bias & Variance profiles of Ensemble vs. Bagging models. 
<img width="995" height="552" alt="image" src="https://github.com/user-attachments/assets/c8f6f70c-6656-48b7-8029-5fe3b6b7e6ba" />

Without `A8`
| Bag/Boost | Tuning | Bias_Acc | Bias_Loss | Gap_Acc | Gap_Loss | TestAccuracy |
| --- | --- | --- | --- | --- | --- | --- |
| Bagging | Base | 0.145805 | 0.017418 | 0.149510 | 0.287550 | 0.833073 |
| Bagging | Tuned | 0.295999 | 0.098294 | 0.070082 | 0.104146 | 0.831624 |
| Boosting | Base | 0.086474 | 0.023113 | 0.147813 | 0.410178 | 0.829074 |
| Boosting | Tuned | 0.222761 | 0.077702 | 0.091555 | 0.192633 | 0.830743 |

With `A8`
| Bag/Boost | Tuning | Bias_Acc | Bias_Loss | Gap_Acc | Gap_Loss | TestAccuracy |
| --- | --- | --- | --- | --- | --- | --- |
| Bagging | Base | 0.124287 | 0.014289 | 0.115782 | 0.271231 | 0.869929 |
| Bagging | Tuned | 0.225476 | 0.070214 | 0.063421 | 0.111668 | 0.866365 |
| Boosting | Base | 0.071371 | 0.017482 | 0.118010 | 0.342795 | 0.864508 |
| Boosting | Tuned | 0.273691 | 0.105585 | 0.041288 | 0.090231 | 0.853127 |

## Overall model performance comparison on holdout test set, with and without the dominant feature `A8`.
<img width="1389" height="690" alt="image" src="https://github.com/user-attachments/assets/5352b427-987a-47ea-afcc-fc72285580ff" />
