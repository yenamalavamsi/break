# break using oops
class class1:
    def __init__(self,n,b):
        self.n=n
        self.b=b
    def print_res(self):
        for i in range(1,self.n+1):
             if i==self.b:
                break
             print(i)
def main():
    n=int(input())
    b=int(input())
    obj=class1(n,b)
    print(obj.print_res())
if __name__=="__main__":
    main()
