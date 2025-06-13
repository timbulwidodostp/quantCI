# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Calculate nonparametric confidence intervals for quantiles using fractional order statistics Use quantCI (QuantileNPCI) With (In) R Software
install.packages("QuantileNPCI")
library("QuantileNPCI")
quantCI = read.csv("https://raw.githubusercontent.com/timbulwidodostp/quantCI/main/quantCI/quantCI.csv",sep = ";")
# Estimation Calculate nonparametric confidence intervals for quantiles using fractional order statistics Use quantCI (QuantileNPCI) With (In) R Software
quantCI_1 <- quantCI[quantCI$quantCI_1=="Feather", "quantCI_3"]
quantCI_2 <- quantCI[quantCI$quantCI_1=="Blackstone", "quantCI_3"]
quant <- .5
alpha <- .05
quantCI_1 <- quantCI(quantCI_1, quant, alpha, method = "exact")
quantCI_2 <- quantCI(quantCI_2, quant, alpha, method = "exact")
quantCI_1
quantCI_2
# Calculate nonparametric confidence intervals for quantiles using fractional order statistics Use quantCI (QuantileNPCI) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished