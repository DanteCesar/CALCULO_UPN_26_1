# 📘 Ejercicios de Derivadas Compuestas (Regla de la Cadena)

## Ejemplo 1 (resuelto)
Derivar:

$$\Large f(x)=(3x+2)^4$$  
$$\Large f(x)=\sin(5x)$$  
$$\Large f(x)=(x^2+1)^5$$  
$$\Large f(x)=\sqrt{4x-3}$$  
$$\Large f(x)=e^{2x+1}$$  
$$\Large f(x)=\cos(7x)$$  
$$\Large f(x)=\cos(x^2+3x)$$  
$$\Large f(x)=e^{x^2}$$  
$$\Large f(x)=\ln(2x^3+x)$$  


---

## Ejercicios propuestos
1. $$\Large f(x)=\sin(3x^2+2x)$$  
2. $$\Large f(x)=e^{5x^2-x}$$  
3. $$\Large f(x)=\ln(x^2+4x+1)$$  
4. $$\Large f(x)=\tan(2x^2+1)$$  

---

## Ejemplo 6 (resuelto)
$$f(x)=\sin(\cos(2x))$$  

Solución:
$$f'(x)=-2\sin(2x)\cos(\cos(2x))$$  

---

## Ejemplo 7 (resuelto)
$$f(x)=\left(\ln(x^2+1)\right)^3$$  

Solución:
$$f'(x)=\frac{6x(\ln(x^2+1))^2}{x^2+1}$$  

---

## Ejemplo 8 (resuelto)
$$f(x)=e^{\sin(3x)}$$  

Solución:
$$f'(x)=3\cos(3x)e^{\sin(3x)}$$  

---

## Ejercicios propuestos
1. $$f(x)=\sqrt{\ln(x^2+1)}$$  
2. $$f(x)=\tan(\ln(x^2+2))$$  
3. $$f(x)=\cos^2(\sin x)$$  
4. $$f(x)=e^{\cos(x^3-x)}$$  
5. $$f(x)=\ln(\sin(x^2+1))$$  

---

# ✅ Derivadas implícitas de funciones reales de variable real

---

## 📘 Ejemplo 1: Circunferencia

Sea la función implícita:
$$x^2+y^2=25$$

Derivando respecto de $$x$$:

$$\frac{d}{dx}(x^2)+\frac{d}{dx}(y^2)=\frac{d}{dx}(25)$$

$$2x+2y\frac{dy}{dx}=0$$

Despejando $$\frac{dy}{dx}$$:

$$2y\frac{dy}{dx}=-2x$$

$$\frac{dy}{dx}=-\frac{x}{y}$$

---

## 📘 Ejemplo 2: Relación cúbica

Sea:
$$x^3+y^3=6xy$$

Derivamos:

$$3x^2+3y^2\frac{dy}{dx}=6\left(x\frac{dy}{dx}+y\right)$$

Expandiendo:

$$3x^2+3y^2\frac{dy}{dx}=6x\frac{dy}{dx}+6y$$

Agrupando términos:

$$3y^2\frac{dy}{dx}-6x\frac{dy}{dx}=6y-3x^2$$

Factorizando:

$$\frac{dy}{dx}(3y^2-6x)=6y-3x^2$$

Despejando:

$$\frac{dy}{dx}=\frac{6y-3x^2}{3y^2-6x}$$

Simplificando:

$$\frac{dy}{dx}=\frac{2y-x^2}{y^2-2x}$$

---

## 📘 Ejemplo 3: Función con logaritmo

Sea:
$$\ln(x)+\ln(y)=\ln(10)$$

Derivando:

$$\frac{1}{x}+\frac{1}{y}\frac{dy}{dx}=0$$

Despejando:

$$\frac{1}{y}\frac{dy}{dx}=-\frac{1}{x}$$

$$\frac{dy}{dx}=-\frac{y}{x}$$

---

## 📘 Ejemplo 4: Función trigonométrica

Sea:
$$\sin(xy)=x$$

Derivamos usando regla de la cadena:

$$\cos(xy)\cdot\frac{d}{dx}(xy)=1$$

$$\cos(xy)\cdot\left(x\frac{dy}{dx}+y\right)=1$$

Despejando:

$$x\cos(xy)\frac{dy}{dx}+\;y\cos(xy)=1$$

$$x\cos(xy)\frac{dy}{dx}=1-y\cos(xy)$$


# ✅ Ejercicios: Derivación Implícita

---

1. $$x^2+y^2=16$$  
2. $$x^2+xy=10$$  
3. $$x^2+3y=7$$  
4. $$xy=5$$  
5. $$x^2+y^3=9$$  

---

1. $$x^3+y^3=6xy$$  
2. $$\frac{x}{y}+y=3$$  
3. $$\ln(x)+\ln(y)=2$$  
4. $$x^2y+y^2=4$$  
5. $$e^y+x^2y=1$$  

---

1. $$\sin(xy)=x$$  
2. $$\cos(x+y)=xy$$  
3. $$\tan(xy)=y$$  
4. $$x\sin(y)=y\cos(x)$$  

---

1. $$x^2y+xy^2=10$$  
2. $$e^{xy}+x^2+y^2=5$$  
3. $$\ln(x+y)+xy=0$$  
4. $$x^3+y^3+3xy=7$$  
5. $$y^x+x^y=10$$  

---

1. $$\sin(xy)+e^{x+y}=x^2$$  
2. $$x^2\ln(y)+y^2\ln(x)=5$$  
3. $$\cos(xy)+xy^2=e^x$$  
4. $$x^2y^2+\ln(x+y)=3$$  

---

## ✅ Ejercicios tipo examen (estructura formal)

Sea la relación implícita:

### Problema 1
$$x^2+y^2+xy=7$$

a) Derive implícitamente  
b) Determine $$\frac{dy}{dx}$$  
c) Evalúe en el punto $$(1,2)$$  

---

### Problema 2
$$e^{xy}+x^2y=4$$  

a) Aplique derivación implícita  
b) Despeje $$\frac{dy}{dx}$$  

---

### Problema 3
$$\ln(x+y)+xy=0$$  

a) Derive ambos lados  
b) Exprese $$\frac{dy}{dx}$$ de forma simplificada  

---

## ✅ Observación

En todos los ejercicios:
- Considere $$y$$ como función de $$x$$  
- Aplique regla del producto, cadena o cociente cuando corresponda  
- Agrupe términos con $$\frac{dy}{dx}$$  
- Despeje explícitamente $$\frac{dy}{dx}$$  

---
``

---

# ✅ Sugerencias
- Identificar la función interna
- Derivar la función externa
- Multiplicar por la derivada de la interna
- Repetir si hay varias capas
