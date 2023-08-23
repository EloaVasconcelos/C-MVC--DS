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




 private string Telefone { get; set; }



[Display(Name = "Email")]
[RegularExpression(@"\w+([-+.']\w+)*@\w+([-.]\w+)*\.\w+([-.]\w+)*")]
private string Email { get; set; }



private string CPF { get; set; }

private int DataNascimento { get; set; }









    }
}
