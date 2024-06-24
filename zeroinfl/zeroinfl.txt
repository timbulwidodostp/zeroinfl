# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Zero-inflated Poisson regression Use zeroinfl With (In) R Software
install.packages("pscl")
library("pscl")
zeroinfl = read.csv("https://raw.githubusercontent.com/timbulwidodostp/zeroinfl/main/zeroinfl/zeroinfl.csv",sep = ";")
# Estimation Zero-inflated Poisson regression Use zeroinfl With (In) R Software
zeroinfl <- zeroinfl(count ~ child + camper | persons, data = zeroinfl)
summary(zeroinfl)
# Zero-inflated Poisson regression Use zeroinfl With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished