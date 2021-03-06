## Results
This file contains the results for the tests on the GTSRB dataset.

| Command line arguments | accuracy on test set |
| --------------------- | ----- |
|  |  |
| -n -1 | 0.97822644497229 |
|  |  |
|      | 0.96959619952494 |
| --cnn 38,64,100     | 0.97149643705463 |
|  --ms    | 0.9673792557403 |
| --cnn 38,64,100 --ms    | 0.9686460807601 |
|   --no_lnorm   | 0.96809184481394 |
| --cnn 38,64,100  --no_lnorm   | 0.96856690419636 |
|  --ms --no_lnorm   | 0.95954077593032 |
| --cnn 38,64,100 --ms --no_lnorm   | 0.96357878068092 |
|    --no_cnorm  | 0.94631828978622 |
| --cnn 38,64,100   --no_cnorm  | 0.93840063341251 |
|  --ms  --no_cnorm  | 0.94996041171813 |
| --cnn 38,64,100 --ms  --no_cnorm  | 0.94536817102138 |
|   --no_lnorm --no_cnorm  | 0.89263657957245 |
| --cnn 38,64,100  --no_lnorm --no_cnorm  | 0.88558986539984 |
|  --ms --no_lnorm --no_cnorm  | 0.90538400633413 |
| --cnn 38,64,100 --ms --no_lnorm --no_cnorm  | 0.89778305621536 |
|     --mom 0.9 | 0.9695170229612 |
| --cnn 38,64,100    --mom 0.9 | 0.97046714172605 |
|  --ms   --mom 0.9 | 0.96500395882819 |
| --cnn 38,64,100 --ms   --mom 0.9 | 0.96666666666667 |
|   --no_lnorm  --mom 0.9 | 0.96809184481394 |
| --cnn 38,64,100  --no_lnorm  --mom 0.9 | 0.96555819477435 |
|  --ms --no_lnorm  --mom 0.9 | 0.95803642121932 |
| --cnn 38,64,100 --ms --no_lnorm  --mom 0.9 | 0.96302454473476 |
|    --no_cnorm --mom 0.9 | 0.94101346001584 |
| --cnn 38,64,100   --no_cnorm --mom 0.9 | 0.93562945368171 |
|  --ms  --no_cnorm --mom 0.9 | 0.94782264449723 |
| --cnn 38,64,100 --ms  --no_cnorm --mom 0.9 | 0.93927157561362 |
|   --no_lnorm --no_cnorm --mom 0.9 | 0.90261282660333 |
| --cnn 38,64,100  --no_lnorm --no_cnorm --mom 0.9 | 0.87466349960412 |
|  --ms --no_lnorm --no_cnorm --mom 0.9 | 0.89738717339667 |
| --cnn 38,64,100 --ms --no_lnorm --no_cnorm --mom 0.9 | 0.89635787806809 |
|  |  |
| --net idsia_net.lua --cnn 100,150,250,300 | 0.9818685669042 |
| --net idsia_net.lua --cnn 150,200,300,350 | 0.98416468725257 |


This file is generated by the `baseline.lua` script.
