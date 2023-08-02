# deep-dive-into-auc
Bu  repository AUC(Area Under Curve) değerinin threshold-invarient ve scale-invarient özelliklerini anlamak için oluşturulmuştur. Bu amaçlar doğrultusunda oluşturulan görsellştirmeler aşağıda da paylaşılmıştır.

#### Notebook İçeriği
- numpy.random ile verisetinin oluşturulması
- verisetinin LogisticRegression modeline fit edilmesi
- roc_curve metriği ile fpr,tpr ve threshold değerlerinin çekilmesi ve görselleştirilmesi(threshold-invarient)
- feature değerlerinin 100 ile çarpılarak scale edilmiş verisetinin de aynı auc değerine sahip olduğunun gösterilmesi(scale-invarient)



Threshold-invarient-image
  
![threshold_auc](https://github.com/msnunu/deep-dive-into-auc/assets/124269047/0f4b36f8-9517-4139-b62e-d7656c19d228)

Scale-invarient-image
  
![scaled_auc](https://github.com/msnunu/deep-dive-into-auc/assets/124269047/e20bc64e-0fe9-41dd-9ebb-2e7a4e7224f7)
