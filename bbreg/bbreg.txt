# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Bessel regression via EM - Model selected via Discrimination test (DBB) models Use bbreg With (In) R Software
install.packages("bbreg")
library("bbreg")
bbreg = read.csv("https://raw.githubusercontent.com/timbulwidodostp/bbreg/main/bbreg/bbreg.csv",sep = ";")
# Estimation Bessel regression via EM - Model selected via Discrimination test (DBB) models Use bbreg With (In) R Software
bbreg <- bbreg(Dependen ~ Independen_1 + Independen_2, data = bbreg)
summary(bbreg)
# Bessel regression via EM - Model selected via Discrimination test (DBB) models Use bbreg With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished