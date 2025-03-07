datos = read.csv("datosEq1.csv")
head(M, n=10)
R1 = subset(datos, datos$region=="R1")[-1]
R2 = subset(datos, datos$region=="R2")[-1]


