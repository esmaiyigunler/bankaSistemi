class BankaHesabi:
    def __init__(self,sahip,bakiye=0):
        self.sahip=sahip
        self.bakiye=bakiye
    def paraYatir(self,miktar):
        self.bakiye+=miktar
        print(f"{miktar}TL yatırıldı. Güncel bakiye{self.bakiye}TL")
    def paraCek(self,miktar):
        if self.bakiye>=miktar:
            self.bakiye-=miktar
            print(f"{miktar}TL çekildi. Güncel bakiye{self.bakiye}TL")
        else:
            print("Yetersiz bakiye")
    def bakiyeGoster(self):
        print(f"{self.sahip} hesabının güncel bakiyesi:{self.bakiye}TL")

hesap1=BankaHesabi("Ahmet",1000)
hesap1.bakiyeGoster()
hesap1.paraYatir(500)
hesap1.paraCek(300)
hesap1.paraCek(1500)
            
