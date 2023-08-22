# C-MVC--DS

 private int CodCliente { get; set; }
        [Display(Name

        private string Nome { get; set; }
        [Display(Name="Nome")]
        [Required(ErrorMessage ="Por Favor preencha seu Nome")]


       private string Endereco { get; set; }


       private string Telefone { get; set; }

        private string Email { get; set; }
        [Display(Name = "Email")]
        [RegularExpression(]


        private string CPF { get; set; }

        private int DataNascimento { get; set; }
    }
}
