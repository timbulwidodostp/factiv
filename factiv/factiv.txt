# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Analyzing Factorial Experiments with Noncompliance Use iv_factorial and iv_finite_factorial (factiv) With (In) R Software
install.packages("factiv")
library("factiv")
# Estimate Analyzing Factorial Experiments with Noncompliance Use iv_factorial and iv_finite_factorial (factiv) With (In) R Software
factiv = read.csv("https://raw.githubusercontent.com/timbulwidodostp/factiv/main/factiv/factiv.csv",sep = ";")
iv_factorial <- iv_factorial(turnout_98 ~ inperson + phone | inperson_rand + phone_rand, data = factiv)
iv_finite_factorial <- iv_finite_factorial(formula = turnout_98 ~ inperson + phone | inperson_rand + phone_rand, data = factiv)
summary(iv_factorial)
summary(iv_finite_factorial)
# Analyzing Factorial Experiments with Noncompliance Use iv_factorial and iv_finite_factorial (factiv) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished