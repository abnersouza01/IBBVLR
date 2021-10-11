## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/abnersouza01/treinamento-html/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/abnersouza01/treinamento-html/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

<!DOCTYPE html>
<html lang="pt-br">
    <head>
        <meta charset="utf-8">
        <meta name="description" content="TREINAMENTO HTML">
        <title>AGENDA DE TREINAMENTO</title>
		<link type=text rel=stylesheet href=estilos.css>
    </head>

<body> 

<h1 
style=color:blue> CURSO DE HTML5/CSS/JAVASCRIPT.
</h1>


 <form> 
 <h1 style =color:red>  <p class= "html"> EXEMPLO DE FORMULÁRIO </h1>
 
	<h2> <nobr>
	Código:     <input type="number" name=code value="Ex. 000-000." size="2" maxlength="7" /> 
	</nobr> </h2>
	
	<h2><nobr>
	Nome:   
	<input type="text" name=myText value="Primeiro nome." size=15> 
		
	<input type="text" name=myText value="Seu último nome." size=15> 
	</nobr></h2>
    
	<h2><nobr>
	Endereço:   
		<input type="textarea" value="Nome da rua." maxlength=68 size=57 />
		</nobr>   
	
		<h5> NÃO SABE SEU ENDEREÇO? <button> <a href= https://buscacepinter.correios.com.br/app/endereco/index.php>CLIQUE AQUI</button> </a>
		</h5>
	
		<p>Númeroº:
		<nobr> <input type="number" value="Número da casa." maxlength=1 size=2 </p>  
		</nobr>  
		
		<p>Bairro:<nobr> <input type="text" value="Bairro." maxlength=37 size=28 </p>    
		</nobr>
		
		<p>Cidade:<nobr> <input type="text" value="Cidade." maxlength=25 size=20 </p> 
		</nobr>
		
		<p>Estado:<nobr> <input type="text" value="Estado." maxlength=25 size=”50” /> 
		</nobr> </p>
	
	
		<nobr> 
	<p> Cep:<input type="number" value="CEP." maxlength="08" size=”0” accesskey=”a” /> 
		</nobr>
	</p>
	
	<h2>
		Religião:
		<select name=religião>
		<option value="catolico">Cristã Protestante</option>
		<option>Cristã Católico</option>
		<option>Cristã Outra</option>
		<option>Budista</option>
		<option>Outra</option>
		</select>
	</h2>

	<h2>
		Sexo:
		<input type="radio" name="sex" value="male" > Masculino
		
		<input type="radio" name="sex" value="female"> Feminino
	
	</h2>


	<h2 class="descreva">
	Descreva um pouco sobre você. 
	</h2>

		<h3>
		<textarea rows="5" cols="40" class="descreva">
Quais são seus objetivos, projetos e sonhos para o futuro?
		</textarea>
		</h3>

<button> VOLTAR </button>
<button> AVANÇAR </button>

</form>    
    
	</body>


</html>
