# lisp
```lisp 
;15 Определите функцию, вычисляющую скалярное произведение векторов, заданых списками целых чисел
(defun scal-prod (v1 v2)
  (+ (* (car v1) (car v2)) (* (cadr v1) (cadr v2))))
  
  (print(scale-prod '(1 2) '(3 4)))
  
  ;22 Определите функцию, которая обращает список (a b c) и разбирает его на уровни (((c) b) a)
  (defun rever (lst)
  (cond
  ((atom (cdr list)) lst)
  (t (list (rever (cdr lst)) (car lst)))
  )
  )
  
  (print (rever '(2 3 4 5)))
  (print (rever '(2 3)))
  (print (rever ()))
```
