# Risk-Based Authentication Project (AWS Miuul Bootcamp - Capstone Project)

The <b>Risk-Based Authentication (RBA)</b> project is a system designed to <b>secure payment transactions</b> by creating a risk score based on the cardholder's previous transactions. Each <b>transaction</b> is evaluated within defined rules, and a risk level is determined based on the cardholder's past behavior. This <b>risk score</b> becomes a critical factor influencing payment success, with additional security steps applied for high-risk transactions and smoother customer experiences provided for low-risk transactions. The <b>goal</b> of this method is to enhance payment security, minimize fraud attempts, and protect genuine users.

## Example Scenario 1:
John typically does not make electronic device purchases online; he mainly buys clothing or lower-cost items. However, an attempt is made to purchase a computer for ₺39,999 from John's card suddenly. In this case, the RBA system calculates a risk score and directs the user to a verification step. Once verified, the transaction can be completed.

## Example Scenario 2:
John frequently shops for clothes. The RBA system observes that his previous purchases, including clothing, have not been of a high quantity or cost. In this scenario, the RBA calculates a risk score, and if it falls below a predefined threshold, the transaction can be completed without user verification.

## Example Scenario 3:
Assuming a system rule specifies a risk score of 20 for transactions within Istanbul and a risk score of 50 for transactions over ₺1,000, the RBA calculates the risk score. If the calculated risk score is below the defined threshold, the transaction can be completed without user verification. If it exceeds the threshold, the user must be directed to a verification step before completing the transaction.

This method aims to increase payment security, minimize fraudulent activities, and protect real users.


# 🏛️ AWS Infrastructure
![rba](https://github.com/risk-based-authentication/.github/assets/61833677/b741e80e-2f18-4d72-89f4-5011d02e6639)

## 💻 Technical Requirements

- **Front-End:** `React.js`, `TypeScript`
- **DevOps:** `Amazon Web Services (AWS)`, `AWS Lambda`, `AWS Step Functions`, `AWS SNS`, `AWS Secrets Manager`, `AWS DynamoDB`, `AWS IAM`, `AWS S3 Bucket`


  
### Contributors
- [Zeynep Deniz](https://github.com/deniizeynep)
- [Metehan Aydemir](https://github.com/Matthewsannn)
- [Ali Anıl Hazar](https://github.com/anilhazar)
- [Emre Yılmaz](https://github.com/emreylmaz)
- [Agit Rubar Demir](https://github.com/agitrubard)
- [Sercan Noyan Germiyanoğlu](https://github.com/Rapter1990)
