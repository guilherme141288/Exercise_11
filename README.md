# Exercise_11

#measuring amount of paint for a wall

lar = float (input ('qual a largura da parede?  '))
alt = float (input ('qual a altura da parede?  '))
altlar = float (lar * alt)
print ('sua parede tem a dimenção de {}m x {}m e sua area é de {:.2f}m2' .format (lar , alt , altlar))
print ('para pintar esse parede e necessario {:.1f} litros de tinta' .format (altlar / 2 
