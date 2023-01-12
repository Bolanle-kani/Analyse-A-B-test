# Analyse A/B test results

### Overview of the project

 A/B test run by an e-commerce website was analysed. The company has developed a new web page in order to try and increase the number of users who "convert," meaning the number of users who decide to pay for the company's product. The aim of this project is to help the company understand if they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.



### Conclusion <br><br>
- All of the p-values are greater than 0.05 therefore none of the variables are statistically significant.
- There's no significant impact of the countries and new page on conversion rates. The company shouldn't implement this new page as there is no conclusive evidence that it is better than the old page.
- If an individual is in canada, they are 0.951 more likely to be converted than if they aare in UK, holding all other variables constant.
- If an individual is in canada, they are 0.96 more likely to be converted than if they aare in US, holding all other variables constant.
- For every one point increase in ab_page, an individual is 0.985 more likely to be converted, holding all other variables constant.
- By looking at the odds ratio of the interaction between country and ab_page, we have an equal chance of the ab_page converting users in each country(0.985, 1.052, 1.042). We thus fail to reject the null hypothesis; the new page does not convert more than the old page.



### Author
[Omobolanle Komolafe (Adeyemi)](https://github.com/Bolanle-kani)
