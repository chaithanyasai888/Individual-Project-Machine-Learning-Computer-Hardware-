# Individual-Project-Machine-Learning-Computer-Hardware-

# DATA SET INFORMATION : 
Computer Hardware Data Set: The estimated relative performance values using below features.

## ATTRIBUTES INFORMATION

1. vendor name: 30 (adviser, amdahl,apollo, basf, bti, burroughs, c.r.d, cambex, cdc, dec,dg, formation, four-phase, gould, honeywell, hp, ibm, ipl, magnuson,microdata, nas, ncr, nixdorf, perkin-elmer, prime, siemens, sperry,sratus, wang)
2. Model Name: many unique symbols
3. MYCT: machine cycle time in nanoseconds (integer)
4. MMIN: minimum main memory in kilobytes (integer)
5. MMAX: maximum main memory in kilobytes (integer)
6. CACH: cache memory in kilobytes (integer)
7. CHMIN: minimum channels in units (integer)
8. CHMAX: maximum channels in units (integer)
9. PRP: published relative performance (integer)
10. ERP: estimated relative performance from the original article (integer)

### EDA
### Splitting the data
### We are calling linear regression and fitting these both variables(independent and dependent). We are using RMSE and r^2 value to validate our findings
### We are plotting the line a between predicted and test value. If they are same, it should be a stright line. But this is how our predictions looks like. The 45 degree line shows test=pred
### finally checking for all the regression models
