'''import turtle
import time
t=turtle.Turtle()

while True:
	x = turtle.numinput("X KORDİNATI" , "X kordinatını giriniz: " , default=0)

	y = turtle.numinput("Y KORDİNATI" , "Y kordinatını giriniz: " , default=0)
	
	kenar = turtle.numinput("KENAR UZUNLUĞU" , "Kenar uzunluğu giriniz: " , default=200)
	
	acı = turtle.numinput("AÇI" , "Dönmek istediğiniz açıyı giriniz: " , default=90)
	
	hız = turtle.numinput("ÇİZİM HIZI" , "Çizim hızını giriniz(0 ile 10 arası): " , default=0)
	
	dönme_sayısı_1 = turtle.numinput("DÖNME SAYISI" , "Kaç kez dönmek istediğini seçiniz:  " , default=0)
	
	dönme_sayısı=int(dönme_sayısı_1)
	
	renk = turtle.textinput("RENK" , "Çizimin rengini seçiniz: ")
	
	t.color(renk)
	t.speed(hız)
	
	t.penup()
	t.goto(x , y)
	t.pendown()
	
	for i in range(dönme_sayısı):
		t.forward(kenar)
		t.left(acı)'''