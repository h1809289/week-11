
class Vehicle():
    
    def __init__(self, name, color, brand, engineSize):
        self.name = name
        self.color = color
        self.brand = brand
        self.engineSize = engineSize

    def showDetails(self):       
        print(self.name,self.color,self.brand, self.engineSize)

for i in range(1,5):
    name = input ("Enter name of vehicle: ")
    color = input ("Enter color of vehicle: ")
    brand = input ("Enter brand of vehicle: ")
    engineSize = input ("Enter the size of the engine: ")
    i = Vehicle (name, color, brand, engineSize)
    i.showDetails()
