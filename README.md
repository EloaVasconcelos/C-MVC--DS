# C-MVC--DS

 private ushort CodCliente { get; set; }
        [Display(Name




[Display(Name="Nome do Cliente ")]
[Required(ErrorMessage ="Por Favor preencha seu Nome")]
private string Nome { get; set; }


[Display(Name="Endereço")

private string Endereco { get; set; }
[Required(ErrorMessage ="Por Favor preencha seu Nome")]
   private string Telefone { get; set; }

        private string Email { get; set; }
        [Display(Name = "Email")]
        [RegularExpression(]


        private string CPF { get; set; }

        private int DataNascimento { get; set; }
    }
}
