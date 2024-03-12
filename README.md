print("         .           ")
print("-- calculadora de IMC --")
print("         .           ")


peso = float(input("digite seu peso"))
altura = float(input("digite sua altura"))
IMC = peso/(altura*altura)






if IMC <= 18.5:
   print("você está muito magro, clique em saiba mais para dicas de como melhorar sua saúde de forma descomplicada....saiba mais....")
elif IMC >= 18.5 and IMC <= 24.9:
   print("seu peso está na média, clique em saiba mais para saber como manter uma vida saudável de forma descomplicada....saiba mais....")
elif IMC <= 25.0 and IMC<= 29.9:
   print("seu  peso está elevado, clique em saiba mais para dicas de como estabilizar seu peso de forma dedscomplicada....saiba mais....")
elif IMC  <= 30.0 and IMC <39.9:
   print("você está em obesidadeI, procure um médico e clique em saiba mais para dicas de como estabilizar seu peso de forma descomplicada....saiba mais....")
elif IMC >= 40.0:
   print("você está em obesidadeII, procure um médico e clique em saiba mais para dicas de como estabilizar seu peso de forma descomplicada....siba mais....")
else:
   print("error")

