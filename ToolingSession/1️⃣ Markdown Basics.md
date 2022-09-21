# Markdown basics
^ Heading 1
## Heading 2 
### Heading 3 etc.

**bold** Ctrl + b

*italic* Ctrl + i

~~strikethrough~~ 

==highlight==

blockquote
> Alea iacta est. 🎲

dividers:

---

- bullet
- points

1. ordered
2. list

- [ ] Todo
- [ ] lists
Ctrl + Enter 

 
## tables:
| animal | size   | sound   |
| ------ | ------ | ------- |
| 🐁     | small  | squeak  |
| 🐈     | medium | meow    |
| 🐘     | big    | trumpet |
recommended: advanced tables plugin

## code:

```python
def fibonacci(n):
	if n < 0:
		print("Incorrect input")
	elif n == 0:
		return 0
	elif n == 1 or n == 2:
		return 1
	else:
		return fibonacci(n - 1) + fibonacci(n - 2)

print(fibonacci(9))
```


## $\LaTeX$ using \$\$
e.g. $E = mc^2$
