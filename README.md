# Setup instructions



* install mvn as per instructions from https://maven.apache.org/install.html

* git clone https://github.com/EdgarLopezPhD/PaySim.git

* cd PaySim

* mvn clean install

* java -classpath /Users/I506629/Git/PaySim/target/classes:/Users/I506629/SAPDevelop/maven/repository/com/github/eclab/mason/0663315/mason-0663315.jar:/Users/I506629/SAPDevelop/maven/repository/org/apache/tinkerpop/tinkergraph-gremlin/3.3.4/tinkergraph-gremlin-3.3.4.jar:/Users/I506629/SAPDevelop/maven/repository/org/apache/tinkerpop/gremlin-core/3.3.4/gremlin-core-3.3.4.jar:/Users/I506629/SAPDevelop/maven/repository/org/apache/tinkerpop/gremlin-shaded/3.3.4/gremlin-shaded-3.3.4.jar:/Users/I506629/SAPDevelop/maven/repository/commons-configuration/commons-configuration/1.10/commons-configuration-1.10.jar:/Users/I506629/SAPDevelop/maven/repository/commons-lang/commons-lang/2.6/commons-lang-2.6.jar:/Users/I506629/SAPDevelop/maven/repository/commons-collections/commons-collections/3.2.2/commons-collections-3.2.2.jar:/Users/I506629/SAPDevelop/maven/repository/org/yaml/snakeyaml/1.15/snakeyaml-1.15.jar:/Users/I506629/SAPDevelop/maven/repository/org/javatuples/javatuples/1.2/javatuples-1.2.jar:/Users/I506629/SAPDevelop/maven/repository/com/carrotsearch/hppc/0.7.1/hppc-0.7.1.jar:/Users/I506629/SAPDevelop/maven/repository/com/jcabi/jcabi-manifests/1.1/jcabi-manifests-1.1.jar:/Users/I506629/SAPDevelop/maven/repository/com/jcabi/jcabi-log/0.14/jcabi-log-0.14.jar:/Users/I506629/SAPDevelop/maven/repository/com/squareup/javapoet/1.8.0/javapoet-1.8.0.jar:/Users/I506629/SAPDevelop/maven/repository/net/objecthunter/exp4j/0.4.8/exp4j-0.4.8.jar:/Users/I506629/SAPDevelop/maven/repository/org/slf4j/jcl-over-slf4j/1.7.21/jcl-over-slf4j-1.7.21.jar:/Users/I506629/SAPDevelop/maven/repository/org/apache/commons/commons-lang3/3.3.1/commons-lang3-3.3.1.jar:/Users/I506629/SAPDevelop/maven/repository/org/slf4j/slf4j-simple/1.7.25/slf4j-simple-1.7.25.jar:/Users/I506629/SAPDevelop/maven/repository/org/slf4j/slf4j-api/1.7.25/slf4j-api-1.7.25.jar org.paysim.paysim.PaySim


* We got output as follows:

PAYSIM: Financial Simulator v2.0

Starting PaySim Running for 720 steps.
Init - Seed 1288553321
NbMerchants: 34749
NbFraudsters: 1000
NbBanks: 5
NbClients: 20000
***************************************************************************************************Step 99
***************************************************************************************************Step 199
***************************************************************************************************Step 299
***************************************************************************************************Step 399
***************************************************************************************************Step 499
***************************************************************************************************Step 599
***************************************************************************************************Step 699
********************
Finished running 720 steps 
----------------------------------------------------
| Estimator      | Action         | Error rate     |
----------------------------------------------------
| Count          | CASH_IN        | 0.16           |
| Count          | CASH_OUT       | 0.20           |
| Count          | DEBIT          | 0.13           |
| Count          | PAYMENT        | 0.22           |
| Count          | TRANSFER       | 0.21           |
----------------------------------------------------
| Average amount | CASH_IN        | 0.07           |
| Average amount | CASH_OUT       | 7.03           |
| Average amount | DEBIT          | 0.02           |
| Average amount | PAYMENT        | 0.06           |
| Average amount | TRANSFER       | 0.58           |
----------------------------------------------------
| Std amount     | CASH_IN        | 0.26           |
| Std amount     | CASH_OUT       | 5.42           |
| Std amount     | DEBIT          | 0.07           |
| Std amount     | PAYMENT        | 0.16           |
| Std amount     | TRANSFER       | 0.17           |
----------------------------------------------------


Nb of clients: 20752 - Nb of steps with transactions: 604
It took: 0.2919 minutes to execute the simulation
Simulation name: PS_20230404203605_1288553321


Starting PaySim Running for 720 steps.
Init - Seed 1288570887
NbMerchants: 34749
NbFraudsters: 1000
NbBanks: 5
NbClients: 20000
***************************************************************************************************Step 99
***************************************************************************************************Step 199
***************************************************************************************************Step 299
***************************************************************************************************Step 399
***************************************************************************************************Step 499
***************************************************************************************************Step 599
***************************************************************************************************Step 699
********************
Finished running 720 steps 
----------------------------------------------------
| Estimator      | Action         | Error rate     |
----------------------------------------------------
| Count          | CASH_IN        | 0.16           |
| Count          | CASH_OUT       | 0.20           |
| Count          | DEBIT          | 0.14           |
| Count          | PAYMENT        | 0.22           |
| Count          | TRANSFER       | 0.21           |
----------------------------------------------------
| Average amount | CASH_IN        | 0.07           |
| Average amount | CASH_OUT       | 7.05           |
| Average amount | DEBIT          | 0.02           |
| Average amount | PAYMENT        | 0.06           |
| Average amount | TRANSFER       | 0.56           |
----------------------------------------------------
| Std amount     | CASH_IN        | 0.26           |
| Std amount     | CASH_OUT       | 4.52           |
| Std amount     | DEBIT          | 0.07           |
| Std amount     | PAYMENT        | 0.16           |
| Std amount     | TRANSFER       | 0.18           |
----------------------------------------------------


Nb of clients: 20777 - Nb of steps with transactions: 614
It took: 0.28393333333333337 minutes to execute the simulation
Simulation name: PS_20230404203622_1288570887


Starting PaySim Running for 720 steps.
Init - Seed 1288587924
NbMerchants: 34749
NbFraudsters: 1000
NbBanks: 5
NbClients: 20000
***************************************************************************************************Step 99
***************************************************************************************************Step 199
***************************************************************************************************Step 299
***************************************************************************************************Step 399
***************************************************************************************************Step 499
***************************************************************************************************Step 599
***************************************************************************************************Step 699
********************
Finished running 720 steps 
----------------------------------------------------
| Estimator      | Action         | Error rate     |
----------------------------------------------------
| Count          | CASH_IN        | 0.16           |
| Count          | CASH_OUT       | 0.20           |
| Count          | DEBIT          | 0.49           |
| Count          | PAYMENT        | 0.21           |
| Count          | TRANSFER       | 0.21           |
----------------------------------------------------
| Average amount | CASH_IN        | 0.07           |
| Average amount | CASH_OUT       | 6.47           |
| Average amount | DEBIT          | 0.02           |
| Average amount | PAYMENT        | 0.06           |
| Average amount | TRANSFER       | 0.51           |
----------------------------------------------------
| Std amount     | CASH_IN        | 0.26           |
| Std amount     | CASH_OUT       | 5.48           |
| Std amount     | DEBIT          | 0.07           |
| Std amount     | PAYMENT        | 0.16           |
| Std amount     | TRANSFER       | 0.18           |
----------------------------------------------------


Nb of clients: 20782 - Nb of steps with transactions: 611
It took: 0.26633333333333337 minutes to execute the simulation
Simulation name: PS_20230404203639_1288587924


Starting PaySim Running for 720 steps.
Init - Seed 1288603905
NbMerchants: 34749
NbFraudsters: 1000
NbBanks: 5
NbClients: 20000
***************************************************************************************************Step 99
***************************************************************************************************Step 199
***************************************************************************************************Step 299
***************************************************************************************************Step 399
***************************************************************************************************Step 499
***************************************************************************************************Step 599
***************************************************************************************************Step 699
********************
Finished running 720 steps 
----------------------------------------------------
| Estimator      | Action         | Error rate     |
----------------------------------------------------
| Count          | CASH_IN        | 0.16           |
| Count          | CASH_OUT       | 0.20           |
| Count          | DEBIT          | 0.07           |
| Count          | PAYMENT        | 0.22           |
| Count          | TRANSFER       | 0.21           |
----------------------------------------------------
| Average amount | CASH_IN        | 0.08           |
| Average amount | CASH_OUT       | 6.85           |
| Average amount | DEBIT          | 0.02           |
| Average amount | PAYMENT        | 0.06           |
| Average amount | TRANSFER       | 0.54           |
----------------------------------------------------
| Std amount     | CASH_IN        | 0.26           |
| Std amount     | CASH_OUT       | 4.85           |
| Std amount     | DEBIT          | 0.07           |
| Std amount     | PAYMENT        | 0.16           |
| Std amount     | TRANSFER       | 0.18           |
----------------------------------------------------


Nb of clients: 20770 - Nb of steps with transactions: 607
It took: 0.24508333333333335 minutes to execute the simulation
Simulation name: PS_20230404203655_1288603905


Starting PaySim Running for 720 steps.
Init - Seed 1288618611
NbMerchants: 34749
NbFraudsters: 1000
NbBanks: 5
NbClients: 20000
***************************************************************************************************Step 99
***************************************************************************************************Step 199
***************************************************************************************************Step 299
***************************************************************************************************Step 399
***************************************************************************************************Step 499
***************************************************************************************************Step 599
***************************************************************************************************Step 699
********************
Finished running 720 steps 
----------------------------------------------------
| Estimator      | Action         | Error rate     |
----------------------------------------------------
| Count          | CASH_IN        | 0.16           |
| Count          | CASH_OUT       | 0.20           |
| Count          | DEBIT          | 0.11           |
| Count          | PAYMENT        | 0.22           |
| Count          | TRANSFER       | 0.21           |
----------------------------------------------------
| Average amount | CASH_IN        | 0.07           |
| Average amount | CASH_OUT       | 6.67           |
| Average amount | DEBIT          | 0.02           |
| Average amount | PAYMENT        | 0.06           |
| Average amount | TRANSFER       | 0.53           |
----------------------------------------------------
| Std amount     | CASH_IN        | 0.26           |
| Std amount     | CASH_OUT       | 4.84           |
| Std amount     | DEBIT          | 0.07           |
| Std amount     | PAYMENT        | 0.16           |
| Std amount     | TRANSFER       | 0.18           |
----------------------------------------------------


Nb of clients: 20741 - Nb of steps with transactions: 607
It took: 0.23846666666666666 minutes to execute the simulation
Simulation name: PS_20230404203710_1288618611


Process finished with exit code 0

* Simulation Results are generated in output directory of PaySim. Under simulation PS_20230404203710_1288618611

