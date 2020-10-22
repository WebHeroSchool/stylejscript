# stylejscript
---
# Советы по стилю кода
---
1. Используйте пробел между параметрами
 + good example
```
function pow(x, n) {
```
+ bad example
```
function pow(x,n) {
```
2. Не используйте пробел между именем функции и скобками, между скобками и параметрами
 + good example
```
function pow(x, n) {
```
+ bad example
```
function pow ( x, n ) {
```
3. Используйте отступ 2 пробела
 + good example
```
function pow(x, n) {
	result = 1;
```
+ bad example
```
function pow(x,n) {
result = 1;
```
4. Используйте пустую стоку между логическими блоками
 + good example
```
function pow(x,n) {
	let result = 1; 

  	for (let i = 0; i < n; i++) {
```
+ bad example
```
function pow(x,n) {
	let result = 1; 
  	for (let i = 0; i < n; i++) {
```
5. Используйте пробел после for/if/while
 + good example
```
function pow(x,n) {
	let result = 1; 

  	for (let i = 0; i < n; i++) {
```
+ bad example
```
function pow(x,n) {
	let result = 1; 

  	for(let i = 0; i < n; i++) {
```
6. Фигурная скобка на той же строке, после пробела
+ good example
```
function pow(x, n) {
	result = 1;
```
+ bad example
```
function pow(x, n) 
{ result = 1;
```
7. Пробелы вокруг операторов
+ good example
```
function pow(x,n) {
	let result = 1; 

  	for (let i = 0; i < n; i++) {
```
+ bad example
```
function pow(x,n) {
	let result = 1; 

  	for (let i=0; i<n; i++) {
```
8. } else { - без перевода строки
+ good example
```
function pow(x, n) {
  if (n < 0) {
    alert("Отрицательные значения 'n' не поддерживаются");
  } else {
    let result = 1;
```
+ bad example
function pow(x, n) {
  if (n < 0) {
    alert("Отрицательные значения 'n' не поддерживаются");
  } else {
    let result = 1;
```
9. Создавая массив
+ good example
```
const items = [];
```
+ bad example
```
const items = new Array();
```
10. Для создания объекта используйте 
+ good example
```
const item = {};
```
+ bad example
```
const item = new Object();
```
