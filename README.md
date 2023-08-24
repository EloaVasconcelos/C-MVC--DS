# C-MVC--DS

[Display(Name="Código do Cliente)
[Required(ErrorMessage ="Por Favor preencha o Código do Cliente")]
private ushort CodCliente { get; set; }
      


[Display(Name="Nome do Cliente ")]
[Required(ErrorMessage ="Por Favor preencha seu Nome")]
private string Nome { get; set; }


[Display(Name="Endereço")
[Required(ErrorMessage ="Por Favor preencha seu Endereço")]
private string Endereco { get; set; }



[Display(Name="Telenofe")
[Required(ErrorMessage ="Digite seu Telefone")]
[RegularExpression(\(?\d{2}\)?\s)?(\d{4,5}\-\d{4})
private string Telefone { get; set;} 



[Display(Name = "Email")]
[RegularExpression(@"\w+([-+.']\w+)*@\w+([-.]\w+)*\.\w+([-.]\w+)*")]
private string Email { get; set; }


[Display(Name = "CPF")]
[Required(ErrorMessage = " Preencha com seu CPF")]
[StringLength(11)]
private int { get; set; }


[Display(Name = "Data de Nascimento")]
Required(ErrorMessage = "Preencha com sua Data de Nascimento")]
[DisplayFormat(DataFormatString= "{dd/mm/aaa}")]
private DataTime DataNascimento { get; set; }









    }
}
