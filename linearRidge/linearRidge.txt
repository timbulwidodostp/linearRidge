# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Linear ridge regression Use linearRidge (ridge) With (In) R Software
install.packages("ridge")
library("ridge")
# Estimate Linear ridge regression Use linearRidge (ridge) With (In) R Software
linearRidge = read.csv("https://raw.githubusercontent.com/timbulwidodostp/linearRidge/main/linearRidge/linearRidge.csv",sep = ";")
linearRidge <- linearRidge(linearRidge ~ ., data = as.data.frame(linearRidge))
summary(linearRidge)
# Linear ridge regression Use linearRidge (ridge) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished