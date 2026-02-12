# Ejercicio-Resuelto-No-4-
class Edades:
  @staticmethod
  def calcular_edalber(edjuan):
    return (2/3) * edjuan
  @staticmethod
  def calcular_edana(edjuan):
    return (4/3) * edjuan
  @staticmethod
  def calcular_edmama(edjuan, edalber, edana):
    return edjuan + edalber + edana


if __name__ == "__main__":

    edjuan = 9

    edalber = Edades.calcular_edalber(edjuan)
    edana = Edades.calcular_edana(edjuan)
    edmama = Edades.calcular_edmama(edjuan, edalber, edana)

    print(f"LAS EDADES SON:\nALBERTO: {edalber} JUAN: {edjuan}\nANA: {edana} MAMA: {edmama}")
