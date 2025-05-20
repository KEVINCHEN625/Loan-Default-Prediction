# Data Folder Overview

This folder contains two sample datasets:
- `train_sample.csv`
- `testA_sample.csv`

Due to GitHub's file size limit, only the first 1000 rows of each dataset are uploaded here.

### 📥 Full Dataset Download

You can download the complete original datasets from the following links:

- **Dataset:** [(https://tianchi.aliyun.com/competition/entrance/531830/information)]
---

### 📊 Field Descriptions

| Field | 中文释义 | Description |
|-------|-----------|-------------|
| id | 唯一信用证标识 | Unique identifier assigned to each loan record |
| loanAmnt | 贷款金额 | Loan amount |
| term | 贷款期限（年） | Loan term (in years) |
| interestRate | 贷款利率 | Interest rate |
| installment | 分期付款金额 | Installment amount |
| grade | 贷款等级 | Loan grade |
| subGrade | 贷款子等级 | Sub-grade of the loan |
| employmentTitle | 就业职称 | Employment title |
| employmentLength | 就业年限（年） | Length of employment (years) |
| homeOwnership | 房屋所有权状况 | Home ownership status provided by the borrower |
| annualIncome | 年收入 | Annual income |
| verificationStatus | 验证状态 | Income verification status |
| issueDate | 贷款发放月份 | Loan issue month |
| purpose | 贷款用途 | Purpose category specified by the borrower |
| postCode | 邮政编码前三位 | First 3 digits of the borrower's postal code |
| regionCode | 地区编码 | Region code |
| dti | 债务收入比 | Debt-to-income ratio |
| delinquency_2years | 过去2年违约事件数 | Number of delinquencies (30+ days) in the past 2 years |
| ficoRangeLow | FICO评分下限 | Lower bound of the FICO score range at loan issuance |
| ficoRangeHigh | FICO评分上限 | Upper bound of the FICO score range at loan issuance |
| openAcc | 未结信用额度数量 | Number of open credit lines in the borrower's credit file |
| pubRec | 贬损公共记录数量 | Number of derogatory public records |
| pubRecBankruptcies | 公开破产记录数 | Number of public bankruptcy records |
| revolBal | 信贷周转余额 | Total revolving balance |
| revolUtil | 信贷额度使用率 | Revolving line utilization rate |
| totalAcc | 总信用账户数 | Total number of credit lines in the credit file |
| initialListStatus | 初始列表状态 | Initial listing status of the loan |
| applicationType | 申请类型 | Indicates whether the loan is an individual or joint application |
| earliestCreditLine | 最早信用记录月份 | Month of the borrower's earliest credit line |
| title | 贷款名称 | Loan title provided by the borrower |
| policyCode | 策略代码 | Policy code (1 = public product; 2 = not publicly available) |
| n0 - n14 | 匿名特征 | Anonymous behavioral features (n0-n14) derived from borrower behavior counts |

---

Please note that the fields `n0` to `n14` are anonymized features used for modeling purposes.
