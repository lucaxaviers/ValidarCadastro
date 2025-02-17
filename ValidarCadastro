let aluno1={
    nome:"Lucas Rodrigues Xavier",
    idade:"17",
    cursando:["TC","BD","IA"],
    presença: ["2022-01-01", "2022-01-02", "2022-01-03", "2022-01-04"],
    RA:"22230021"
}

let aluno2={
    nome:"Marcos",
    idade:"5",
    cursando:["INFO","ADM"],
    presença: ["2022-01-01"],
    ra:"222848"
}

function validarCadastro(aluno){//validando cadastro(ou quase)
     const response={
     status:"valid",
     message:"Valido",
     aluno: aluno
        
     }
     if(validarNome(aluno) && validarIdade(aluno) && validarIdade(aluno) && validarCursos(aluno) && validarAssiduidade(aluno) && validarRA(aluno)){
        console.log(response)
     }
}
     


function validarNome(aluno){//validando nome
    const tamanho = aluno.nome.lenght
    if(tamanho < 10){
        return console.log('Nome Invalido')
    }
    return true
}

function validarIdade(aluno){//validando
    const idade = aluno.idade
    if(idade < 14){
        return console.log('Idade minima não atingida')
    }
    return true
}
function validarCursos(aluno){//validando
    const cursos = aluno.curso
    if(cursos < 3){
        return console.log('Cursos insuficientes')
    }
    return true
}

function validarAssiduidade(aluno){//validando
    const assiduidade = aluno.assiduidade
    if(assiduidade < 2){
       return console.log('Assiduidade não atingida')
    }
    return true
}

function validarRA(aluno){//validando
    const ra = aluno.ra.lenght
    if(ra <7){
        return console.log('RA Invalido')
    }
    return true
}

