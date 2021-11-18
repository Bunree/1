# 1class Table:

    def __init__(self, l = 1, w = 1, h = 1):
        self.leght = l
        self.widht = w
        self.height = h
    def sum(self):
        print(self.leght*self.widht*self.height*0.4)


class kitchTable:
    def __init__(self, l, w, h, n = 2):
        Table.__init__(self, l, w, n)
        self.namber = n
    def resalt(self):
        print(self.leght*self.widht*self.height*0.4*self.namber)


table1 = Table(125, 65, 200)
table1.sum()


table2 = kitchTable(125, 65, 200, 3)
table2.resalt()
