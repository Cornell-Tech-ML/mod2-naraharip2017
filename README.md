[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/YFgwt0yY)
# MiniTorch Module 2

<img src="https://minitorch.github.io/minitorch.svg" width="50%">


* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module2/module2/

This assignment requires the following files from the previous assignments. You can get these by running

```bash
python sync_previous_module.py previous-module-dir current-module-dir
```

The files that will be synced are:

        minitorch/operators.py minitorch/module.py minitorch/autodiff.py minitorch/scalar.py minitorch/scalar_functions.py minitorch/module.py project/run_manual.py project/run_scalar.py project/datasets.py

# Task 2.5 Results

## Simple Data Set

### Parameters
- 50 points
- 2 hidden layers
- 0.1 Learning Rate
- 1000 epochs

### Initial Setting

<img src="readmeImages/simpleInitial.png" width="75%">

### Trained Results

<img src="readmeImages/simpleTrained.png" width="75%">

<img src="readmeImages/simpleLoss.png" width="100%">


### Logs

```
Epoch: 10/1000, loss: 36.08883357160892, correct: 26
Epoch: 20/1000, loss: 35.23507040275149, correct: 26
Epoch: 30/1000, loss: 34.81482890727404, correct: 26
Epoch: 40/1000, loss: 34.573858583525315, correct: 26
Epoch: 50/1000, loss: 34.434436681325145, correct: 26
Epoch: 60/1000, loss: 34.35129888588819, correct: 26
Epoch: 70/1000, loss: 34.298813100164516, correct: 26
Epoch: 80/1000, loss: 34.2628441071759, correct: 26
Epoch: 90/1000, loss: 34.23519152958362, correct: 26
Epoch: 100/1000, loss: 34.21166403343843, correct: 26
Epoch: 110/1000, loss: 34.190336533950955, correct: 26
Epoch: 120/1000, loss: 34.16964781894762, correct: 26
Epoch: 130/1000, loss: 34.148794686384726, correct: 26
Epoch: 140/1000, loss: 34.1273984219812, correct: 26
Epoch: 150/1000, loss: 34.105162733977934, correct: 26
Epoch: 160/1000, loss: 34.0818662830296, correct: 26
Epoch: 170/1000, loss: 34.0573743327649, correct: 26
Epoch: 180/1000, loss: 34.03154553419217, correct: 26
Epoch: 190/1000, loss: 34.00433088193091, correct: 26
Epoch: 200/1000, loss: 33.975566546147434, correct: 26
Epoch: 210/1000, loss: 33.945154887384085, correct: 26
Epoch: 220/1000, loss: 33.912915576896914, correct: 26
Epoch: 230/1000, loss: 33.87882784010574, correct: 26
Epoch: 240/1000, loss: 33.842645498657426, correct: 26
Epoch: 250/1000, loss: 33.80427224841549, correct: 26
Epoch: 260/1000, loss: 33.76349987825598, correct: 26
Epoch: 270/1000, loss: 33.72020156345839, correct: 26
Epoch: 280/1000, loss: 33.6741810791906, correct: 26
Epoch: 290/1000, loss: 33.625201942596696, correct: 26
Epoch: 300/1000, loss: 33.57306968747329, correct: 26
Epoch: 310/1000, loss: 33.51753147856104, correct: 26
Epoch: 320/1000, loss: 33.45831581660316, correct: 26
Epoch: 330/1000, loss: 33.39513783942978, correct: 26
Epoch: 340/1000, loss: 33.32766957332252, correct: 26
Epoch: 350/1000, loss: 33.25555333835448, correct: 27
Epoch: 360/1000, loss: 33.17839808587355, correct: 31
Epoch: 370/1000, loss: 33.095775708407245, correct: 31
Epoch: 380/1000, loss: 33.00727515302363, correct: 34
Epoch: 390/1000, loss: 32.91264054375584, correct: 34
Epoch: 400/1000, loss: 32.811218900391125, correct: 36
Epoch: 410/1000, loss: 32.70246110156298, correct: 36
Epoch: 420/1000, loss: 32.585882080661854, correct: 36
Epoch: 430/1000, loss: 32.460777493207914, correct: 37
Epoch: 440/1000, loss: 32.3265222165813, correct: 38
Epoch: 450/1000, loss: 32.18386372202374, correct: 38
Epoch: 460/1000, loss: 32.033335455870244, correct: 39
Epoch: 470/1000, loss: 31.8737919726184, correct: 39
Epoch: 480/1000, loss: 31.70156786359677, correct: 39
Epoch: 490/1000, loss: 31.516956890515722, correct: 39
Epoch: 500/1000, loss: 31.319315780853263, correct: 40
Epoch: 510/1000, loss: 31.108026798395503, correct: 40
Epoch: 520/1000, loss: 30.880238346184846, correct: 40
Epoch: 530/1000, loss: 30.63736033825248, correct: 40
Epoch: 540/1000, loss: 30.37678631420686, correct: 40
Epoch: 550/1000, loss: 30.097304068659906, correct: 41
Epoch: 560/1000, loss: 29.80038073392042, correct: 41
Epoch: 570/1000, loss: 29.48237299086018, correct: 42
Epoch: 580/1000, loss: 29.143182940640106, correct: 42
Epoch: 590/1000, loss: 28.783109372854195, correct: 43
Epoch: 600/1000, loss: 28.402614279897627, correct: 43
Epoch: 610/1000, loss: 28.00011955058376, correct: 43
Epoch: 620/1000, loss: 27.575350399299282, correct: 43
Epoch: 630/1000, loss: 27.126921067300596, correct: 43
Epoch: 640/1000, loss: 26.656380606013485, correct: 43
Epoch: 650/1000, loss: 26.16219980747625, correct: 43
Epoch: 660/1000, loss: 25.644866656544114, correct: 43
Epoch: 670/1000, loss: 25.11181721101126, correct: 43
Epoch: 680/1000, loss: 24.562814708708558, correct: 44
Epoch: 690/1000, loss: 24.001732594768534, correct: 44
Epoch: 700/1000, loss: 23.424575916256867, correct: 44
Epoch: 710/1000, loss: 22.843138972205683, correct: 44
Epoch: 720/1000, loss: 22.246239537471887, correct: 44
Epoch: 730/1000, loss: 21.643235042287557, correct: 44
Epoch: 740/1000, loss: 21.03926089042005, correct: 45
Epoch: 750/1000, loss: 20.442138159247435, correct: 44
Epoch: 760/1000, loss: 19.853584379485763, correct: 45
Epoch: 770/1000, loss: 19.27617103812969, correct: 45
Epoch: 780/1000, loss: 18.706421078997753, correct: 45
Epoch: 790/1000, loss: 18.150227196344144, correct: 45
Epoch: 800/1000, loss: 17.598462071088942, correct: 46
Epoch: 810/1000, loss: 17.056257901850728, correct: 47
Epoch: 820/1000, loss: 16.52194754360948, correct: 47
Epoch: 830/1000, loss: 15.998867863717845, correct: 48
Epoch: 840/1000, loss: 15.487759648671108, correct: 49
Epoch: 850/1000, loss: 14.98853750702091, correct: 49
Epoch: 860/1000, loss: 14.502031513870598, correct: 49
Epoch: 870/1000, loss: 14.026988582983927, correct: 49
Epoch: 880/1000, loss: 13.57253920935301, correct: 49
Epoch: 890/1000, loss: 13.138282324561, correct: 49
Epoch: 900/1000, loss: 12.720721972899888, correct: 49
Epoch: 910/1000, loss: 12.323502492783502, correct: 50
Epoch: 920/1000, loss: 11.94080405554002, correct: 50
Epoch: 930/1000, loss: 11.571738745435386, correct: 50
Epoch: 940/1000, loss: 11.214530652125353, correct: 50
Epoch: 950/1000, loss: 10.871772336794372, correct: 50
Epoch: 960/1000, loss: 10.544601257913943, correct: 50
Epoch: 970/1000, loss: 10.234632708654154, correct: 50
Epoch: 980/1000, loss: 9.935599332012897, correct: 50
Epoch: 990/1000, loss: 9.64916451404238, correct: 50
Epoch: 1000/1000, loss: 9.373797046255262, correct: 50
```

## Diag Data Set

### Parameters
- 50 points
- 2 hidden layers
- 0.5 Learning Rate
- 2000 epochs

### Initial Setting

<img src="readmeImages/diagInitial.png" width="75%">

### Trained Results

<img src="readmeImages/diagTrained.png" width="75%">

<img src="readmeImages/diagLoss.png" width="100%">


### Logs
```
Epoch: 0/2000, loss: 0, correct: 0
Epoch: 10/2000, loss: 19.48726365957854, correct: 45
Epoch: 20/2000, loss: 16.348106039110398, correct: 45
Epoch: 30/2000, loss: 15.974817408114255, correct: 45
Epoch: 40/2000, loss: 15.895096883189037, correct: 45
Epoch: 50/2000, loss: 15.853213771792026, correct: 45
Epoch: 60/2000, loss: 15.813720197675249, correct: 45
Epoch: 70/2000, loss: 15.7708827937184, correct: 45
Epoch: 80/2000, loss: 15.723295522930353, correct: 45
Epoch: 90/2000, loss: 15.670114387752898, correct: 45
Epoch: 100/2000, loss: 15.610469196992527, correct: 45
Epoch: 110/2000, loss: 15.543329823442527, correct: 45
Epoch: 120/2000, loss: 15.467497474435794, correct: 45
Epoch: 130/2000, loss: 15.38154683630707, correct: 45
Epoch: 140/2000, loss: 15.283791241941447, correct: 45
Epoch: 150/2000, loss: 15.17221025925512, correct: 45
Epoch: 160/2000, loss: 15.044393740617627, correct: 45
Epoch: 170/2000, loss: 14.898600235160524, correct: 45
Epoch: 180/2000, loss: 14.73153804283898, correct: 45
Epoch: 190/2000, loss: 14.539865058688983, correct: 45
Epoch: 200/2000, loss: 14.31844457049775, correct: 45
Epoch: 210/2000, loss: 14.068948271399776, correct: 45
Epoch: 220/2000, loss: 13.787439013234083, correct: 45
Epoch: 230/2000, loss: 13.470851550504884, correct: 45
Epoch: 240/2000, loss: 13.117999337857032, correct: 45
Epoch: 250/2000, loss: 12.716198677022039, correct: 45
Epoch: 260/2000, loss: 12.26814195422128, correct: 45
Epoch: 270/2000, loss: 11.777806855839192, correct: 45
Epoch: 280/2000, loss: 11.244341433084587, correct: 45
Epoch: 290/2000, loss: 10.683309616032606, correct: 45
Epoch: 300/2000, loss: 10.091287671902355, correct: 45
Epoch: 310/2000, loss: 9.466875379795077, correct: 45
Epoch: 320/2000, loss: 8.852157183295027, correct: 45
Epoch: 330/2000, loss: 8.25337031428833, correct: 45
Epoch: 340/2000, loss: 7.710277415989268, correct: 45
Epoch: 350/2000, loss: 7.33284739695798, correct: 45
Epoch: 360/2000, loss: 6.900785039347391, correct: 45
Epoch: 370/2000, loss: 6.561485621992055, correct: 48
Epoch: 380/2000, loss: 6.294644278191456, correct: 48
Epoch: 390/2000, loss: 6.067499321712338, correct: 48
Epoch: 400/2000, loss: 5.757279325591353, correct: 48
Epoch: 410/2000, loss: 5.542199987401281, correct: 48
Epoch: 420/2000, loss: 5.331379181464956, correct: 48
Epoch: 430/2000, loss: 5.138932735326348, correct: 48
Epoch: 440/2000, loss: 4.965962102396593, correct: 48
Epoch: 450/2000, loss: 4.80968747414394, correct: 48
Epoch: 460/2000, loss: 4.665568697692098, correct: 48
Epoch: 470/2000, loss: 4.533427543461048, correct: 48
Epoch: 480/2000, loss: 4.411389561619382, correct: 48
Epoch: 490/2000, loss: 4.298235243973663, correct: 48
Epoch: 500/2000, loss: 4.192931218911906, correct: 48
Epoch: 510/2000, loss: 4.094597992436209, correct: 48
Epoch: 520/2000, loss: 4.002477417052319, correct: 49
Epoch: 530/2000, loss: 3.9159164660643766, correct: 49
Epoch: 540/2000, loss: 3.8343525742954703, correct: 49
Epoch: 550/2000, loss: 3.757297617023263, correct: 49
Epoch: 560/2000, loss: 3.6843263619058524, correct: 49
Epoch: 570/2000, loss: 3.615066883644913, correct: 49
Epoch: 580/2000, loss: 3.549192591887214, correct: 49
Epoch: 590/2000, loss: 3.4864163694857644, correct: 49
Epoch: 600/2000, loss: 3.426483599728722, correct: 49
Epoch: 610/2000, loss: 3.3691669943050595, correct: 49
Epoch: 620/2000, loss: 3.314264359307959, correct: 49
Epoch: 630/2000, loss: 3.2615952565433908, correct: 49
Epoch: 640/2000, loss: 3.2109976687025017, correct: 49
Epoch: 650/2000, loss: 3.162325621218647, correct: 49
Epoch: 660/2000, loss: 3.1154471571365745, correct: 49
Epoch: 670/2000, loss: 3.07024260774637, correct: 49
Epoch: 680/2000, loss: 3.026603111793159, correct: 49
Epoch: 690/2000, loss: 2.9844293442212573, correct: 49
Epoch: 700/2000, loss: 2.9436304220385825, correct: 49
Epoch: 710/2000, loss: 2.9041229602957253, correct: 49
Epoch: 720/2000, loss: 2.8658302556043225, correct: 49
Epoch: 730/2000, loss: 2.8286815782622963, correct: 49
Epoch: 740/2000, loss: 2.792611557060734, correct: 49
Epoch: 750/2000, loss: 2.75755964333892, correct: 49
Epoch: 760/2000, loss: 2.72346964292665, correct: 49
Epoch: 770/2000, loss: 2.690289306342864, correct: 49
Epoch: 780/2000, loss: 2.6579699690683984, correct: 49
Epoch: 790/2000, loss: 2.626466234927822, correct: 49
Epoch: 800/2000, loss: 2.595735696640614, correct: 49
Epoch: 810/2000, loss: 2.565738688468111, correct: 49
Epoch: 820/2000, loss: 2.5364380666159785, correct: 49
Epoch: 830/2000, loss: 2.507799013674166, correct: 49
Epoch: 840/2000, loss: 2.4797888639053642, correct: 49
Epoch: 850/2000, loss: 2.4523769466435046, correct: 49
Epoch: 860/2000, loss: 2.4255344454483154, correct: 49
Epoch: 870/2000, loss: 2.399234270990334, correct: 49
Epoch: 880/2000, loss: 2.373450945921926, correct: 49
Epoch: 890/2000, loss: 2.348160565970422, correct: 49
Epoch: 900/2000, loss: 2.3233405705758083, correct: 49
Epoch: 910/2000, loss: 2.2989696285836385, correct: 49
Epoch: 920/2000, loss: 2.2750277567083432, correct: 49
Epoch: 930/2000, loss: 2.251496140871856, correct: 49
Epoch: 940/2000, loss: 2.2283570678430933, correct: 49
Epoch: 950/2000, loss: 2.2055938617813737, correct: 49
Epoch: 960/2000, loss: 2.183190834955876, correct: 49
Epoch: 970/2000, loss: 2.1611332190217936, correct: 49
Epoch: 980/2000, loss: 2.1394070892613484, correct: 49
Epoch: 990/2000, loss: 2.1179993664641774, correct: 49
Epoch: 1000/2000, loss: 2.0968977485043805, correct: 49
Epoch: 1010/2000, loss: 2.076090667268878, correct: 49
Epoch: 1020/2000, loss: 2.0555672479543157, correct: 49
Epoch: 1030/2000, loss: 2.035317270539054, correct: 49
Epoch: 1040/2000, loss: 2.0153311332627903, correct: 49
Epoch: 1050/2000, loss: 1.995599817968736, correct: 49
Epoch: 1060/2000, loss: 1.9761148571823108, correct: 49
Epoch: 1070/2000, loss: 1.9568683028166831, correct: 50
Epoch: 1080/2000, loss: 1.93785269640923, correct: 50
Epoch: 1090/2000, loss: 1.9190610408046818, correct: 50
Epoch: 1100/2000, loss: 1.9004867732105288, correct: 50
Epoch: 1110/2000, loss: 1.882123739558415, correct: 50
Epoch: 1120/2000, loss: 1.8639661822893419, correct: 50
Epoch: 1130/2000, loss: 1.8460086844926322, correct: 50
Epoch: 1140/2000, loss: 1.8282461684388942, correct: 50
Epoch: 1150/2000, loss: 1.8106738835151928, correct: 50
Epoch: 1160/2000, loss: 1.7932873771979085, correct: 50
Epoch: 1170/2000, loss: 1.7760824761801615, correct: 50
Epoch: 1180/2000, loss: 1.7590552684728782, correct: 50
Epoch: 1190/2000, loss: 1.742202086442672, correct: 50
Epoch: 1200/2000, loss: 1.7255194907508418, correct: 50
Epoch: 1210/2000, loss: 1.709004255158702, correct: 50
Epoch: 1220/2000, loss: 1.6926533521652078, correct: 50
Epoch: 1230/2000, loss: 1.6764639394434475, correct: 50
Epoch: 1240/2000, loss: 1.6604333470431532, correct: 50
Epoch: 1250/2000, loss: 1.6445590653269062, correct: 50
Epoch: 1260/2000, loss: 1.6288387336082115, correct: 50
Epoch: 1270/2000, loss: 1.6132701294601903, correct: 50
Epoch: 1280/2000, loss: 1.5978511586641857, correct: 50
Epoch: 1290/2000, loss: 1.5825798457681854, correct: 50
Epoch: 1300/2000, loss: 1.5674543252256687, correct: 50
Epoch: 1310/2000, loss: 1.5524728330861342, correct: 50
Epoch: 1320/2000, loss: 1.5376336992093913, correct: 50
Epoch: 1330/2000, loss: 1.5229353399764975, correct: 50
Epoch: 1340/2000, loss: 1.508376251471043, correct: 50
Epoch: 1350/2000, loss: 1.493955003105441, correct: 50
Epoch: 1360/2000, loss: 1.4796702316677492, correct: 50
Epoch: 1370/2000, loss: 1.4655206357655663, correct: 50
Epoch: 1380/2000, loss: 1.4515049706444183, correct: 50
Epoch: 1390/2000, loss: 1.4376220433591338, correct: 50
Epoch: 1400/2000, loss: 1.4238707082775746, correct: 50
Epoch: 1410/2000, loss: 1.4102498628971651, correct: 50
Epoch: 1420/2000, loss: 1.396758443955508, correct: 50
Epoch: 1430/2000, loss: 1.3833954238174135, correct: 50
Epoch: 1440/2000, loss: 1.3701598071215353, correct: 50
Epoch: 1450/2000, loss: 1.3570506276707264, correct: 50
Epoch: 1460/2000, loss: 1.3440669455510603, correct: 50
Epoch: 1470/2000, loss: 1.331207844465342, correct: 50
Epoch: 1480/2000, loss: 1.3184724292677048, correct: 50
Epoch: 1490/2000, loss: 1.3058598236866574, correct: 50
Epoch: 1500/2000, loss: 1.293369168224712, correct: 50
Epoch: 1510/2000, loss: 1.2809996182233485, correct: 50
Epoch: 1520/2000, loss: 1.2687503420828288, correct: 50
Epoch: 1530/2000, loss: 1.256620519626909, correct: 50
Epoch: 1540/2000, loss: 1.244609340603158, correct: 50
Epoch: 1550/2000, loss: 1.232716003310109, correct: 50
Epoch: 1560/2000, loss: 1.2209397133430109, correct: 50
Epoch: 1570/2000, loss: 1.2092796824504646, correct: 50
Epoch: 1580/2000, loss: 1.1977351274946388, correct: 50
Epoch: 1590/2000, loss: 1.1863052695082816, correct: 50
Epoch: 1600/2000, loss: 1.1749893328420602, correct: 50
Epoch: 1610/2000, loss: 1.1637865443962399, correct: 50
Epoch: 1620/2000, loss: 1.152696132931021, correct: 50
Epoch: 1630/2000, loss: 1.1417173284501965, correct: 50
Epoch: 1640/2000, loss: 1.1308493616531323, correct: 50
Epoch: 1650/2000, loss: 1.1200914634503878, correct: 50
Epoch: 1660/2000, loss: 1.109442864538503, correct: 50
Epoch: 1670/2000, loss: 1.0989027950298438, correct: 50
Epoch: 1680/2000, loss: 1.0884704841335697, correct: 50
Epoch: 1690/2000, loss: 1.0781451598840466, correct: 50
Epoch: 1700/2000, loss: 1.067926048913264, correct: 50
Epoch: 1710/2000, loss: 1.0578123762639915, correct: 50
Epoch: 1720/2000, loss: 1.047803365240617, correct: 50
Epoch: 1730/2000, loss: 1.0378982372948151, correct: 50
Epoch: 1740/2000, loss: 1.0280962119433141, correct: 50
Epoch: 1750/2000, loss: 1.0183965067152352, correct: 50
Epoch: 1760/2000, loss: 1.0087983371266298, correct: 50
Epoch: 1770/2000, loss: 0.9993009166799409, correct: 50
Epoch: 1780/2000, loss: 0.9899034568863179, correct: 50
Epoch: 1790/2000, loss: 0.9806051673087505, correct: 50
Epoch: 1800/2000, loss: 0.9714052556242324, correct: 50
Epoch: 1810/2000, loss: 0.9623029277031352, correct: 50
Epoch: 1820/2000, loss: 0.953297387704203, correct: 50
Epoch: 1830/2000, loss: 0.9443878381836098, correct: 50
Epoch: 1840/2000, loss: 0.935573480216635, correct: 50
Epoch: 1850/2000, loss: 0.9268535135306178, correct: 50
Epoch: 1860/2000, loss: 0.9182271366479, correct: 50
Epoch: 1870/2000, loss: 0.9096935470375935, correct: 50
Epoch: 1880/2000, loss: 0.9012519412750521, correct: 50
Epoch: 1890/2000, loss: 0.8929015152080102, correct: 50
Epoch: 1900/2000, loss: 0.8846414641284083, correct: 50
Epoch: 1910/2000, loss: 0.8764709829490257, correct: 50
Epoch: 1920/2000, loss: 0.8683892663840438, correct: 50
Epoch: 1930/2000, loss: 0.8603955091327723, correct: 50
Epoch: 1940/2000, loss: 0.8524889060658024, correct: 50
Epoch: 1950/2000, loss: 0.8446686524129008, correct: 50
Epoch: 1960/2000, loss: 0.8369339439520109, correct: 50
Epoch: 1970/2000, loss: 0.8292839771987929, correct: 50
Epoch: 1980/2000, loss: 0.8217179495961243, correct: 50
Epoch: 1990/2000, loss: 0.8142350597030998, correct: 50
Epoch: 2000/2000, loss: 0.8068345073830323, correct: 50
```

## Split Data Set

### Parameters
- 50 points
- 2 hidden layers
- 0.5 Learning Rate
- 2000 epochs

### Initial Setting

<img src="readmeImages/diagInitial.png" width="75%">

### Trained Results

<img src="readmeImages/diagTrained.png" width="75%">

<img src="readmeImages/diagLoss.png" width="100%">


### Logs
