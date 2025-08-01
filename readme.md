
Hey Copilot, please scan every HTML and JS file in this folder for links starting with https://teslacapitalfinance.com. 

1. For any href that ends in:
 https://teslacapitalfinance.com/plans       →        #
https://teslacapitalfinance.com/connect-wallet/     →      #
https://teslacapitalfinance.com/import-wallet/        →      #
https://teslacapitalfinance.com/processing-wallet-connection/       →   #
https://teslacapitalfinance.com/about-us/#elementor-action%3Aaction%3Dpopup%3Aopen%26settings%3DeyJpZCI6IjExMzkiLCJ0b2dnbGUiOmZhbHNlfQ%3D%3D     →              #

   replace the entire href value with "#".

2. For any href that ends in:
https://teslacapitalfinance.com/about-us/                                →            aboutus.html
https://teslacapitalfinance.com/contact-us/                                            → contactus.html
https://teslacapitalfinance.com/faqs/                                         →              faqs.html
https://teslacapitalfinance.com/privacy-policy/                        →        privacy-policy.html
https://teslacapitalfinance.com/terms-and-conditions/                  →           Termsandcondition.html

   replace the URL with the corresponding file name (keeping it relative).

3. If any file links to the root URL (`https://teslacapitalfinance.com/`), change that href to `index.html`.

Show me a diff or summary of all changes before you apply them.