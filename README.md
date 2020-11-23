# Práctica git

### **¿Qué comando utilizaste en el paso 11? ¿Por qué?**

Lo he utilizado para deshacer el último commit y dejar mi working copy como estaba antes.

```
git reset --hard HEAD~1
```

### **¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

para ver los pasos que he seguido y ver la referencia del commit.

```
git reflog
```

para moverse al commit que tenía los cambios.

```
git checkout 76e7566
```

para eliminar la rama que tenía los cambios antiguos.

```
git branch -d styled
```

para crear la rama styled.

```
git branch styled
```

me muevo a la rama styled.

```
git checkout styled
```

### **El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

No causó ningún conflicto, porque no se hizo ningún cambio en la rama master con ese mismo archivo.

### **El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Sí causó un conflicto porque git detectó que se había hecho un cambio en ese mismo archivo en dos ramas distintas.

### **El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No causó ningún conflicto porque en master no tiene cambios recientes en ese mismo archivo, tiene cambios antiguos por eso los añade.

### **¿Qué comando o comandos utilizaste en el paso 25?**

Utilice un alias que me había creado.

```
git graph
```

Este es el comando que se utiliza.

```
git log --graph --oneline
```

![Imagen del diagrama](./log.png)

### **El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

Si que es fast forward, porque están en el mismo punto del diagrama y no se pierde lar referencia de esa rama.

### **¿Qué comando o comandos utilizaste en el paso 27?**

```
git reset HEAD~1
```

### **¿Qué comando o comandos utilizaste en el paso 28?**

```
git restore git-nuestro.md
```

### **¿Qué comando o comandos utilizaste en el paso 29?**

```
git branch -D title
```

### **¿Qué comando o comandos utilizaste en el paso 30?**

```
git reflog
git checkout 9f0e3c0
git branch -d master
git checkout -b master
```

### **¿Qué comando o comandos usaste en el paso 32?**

```
git log
git reset --hard HEAD~3
```

### **¿Qué comando o comandos usaste en el punto 33?**

```
git reflog
git checkout 9f0e3c0
```
