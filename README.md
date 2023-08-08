
// /usr/bin/javascript
// # -*- coding: utf-8 -*-

class EngenheiroDeSoftware {
  constructor(nome, idade, cargo, experiencia, linguas) {
    this.nome = nome;
    this.idade = idade;
    this.cargo = cargo;
    this.experiencia = experiencia;
    this.linguas = linguas;
  }

  apresentar() {
    console.log(`👋 Olá! Eu sou o(a) ${this.nome} (${this.idade} anos), um(a) ${this.cargo} com ${this.experiencia} de experiência.`);
    console.log(`💡 Tenho interesse em desenvolvimento de software, algoritmos e sistemas web.`);
    console.log(`🎯 Meu objetivo é aprender e evoluir profissionalmente, buscando as melhores práticas para construir aplicações web de alta qualidade.`);
    console.log(`🔧 Tenho habilidades em resolução de problemas, trabalho em equipe e comunicação efetiva.`);
    console.log(`💻 Algumas das tecnologias que domino incluem JavaScript, Java, HTML, CSS, Git e MySQL.`);
    console.log(`🌐 Sou fluente em ${this.linguas[0]} e tenho conhecimentos intermediários em ${this.linguas[1]}.`);
    console.log(`✉️ Você pode entrar em contato comigo pelo e-mail: enzzoferrarib@hotmail.com.`);
  }
}

const eu = new EngenheiroDeSoftware("Enzzo Ferrari Bertoncello", 20, "Estudante de Engenharia de Software", "2 semestres", ["pt_BR", "en_US"]);
eu.apresentar();


