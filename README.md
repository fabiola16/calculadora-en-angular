# calculadora-en-angular
calculadora hecho en angular
<html>

<head>


<title>Primer proyecto en angular
</title>


</head>


<body>


<div class="navbar-inner">


<h3>


<div  class="center sliding">Calculadora</div>


</h3>

</div>



<div>

<input placeholder="ingresar numero" type ="number"[(ngModel)]="num" />

<input placeholder="ingresar numero" type ="number"[(ngModel)]="num1"/>


</div>


<br>


<div >


<a href="" class="boton_1" (click)="sumar()">sumar +</a>

<a href="" class="boton_1" (click)="restar()">restar -</a>
 
<a href="" class="boton_1" (click)="multiplicar()">multiplicar *</a>


<a href="" class="boton_1" (click)="dividir">dividir /</a>

</div>


<div>
 
Resultado es :{{resultado}}


</div>

</body>


</html>
