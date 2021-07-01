class Joueur
   def __init__(self,personnage, message):
       self.personnage = personnage
       self.message = message

    def action(self, message)
        print("{} : déclare {}".format(self, personnage, message))

J1 = Joueur("Johan")
J1 = action("Que le combat Commence !")
