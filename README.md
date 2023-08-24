# C-MVC--DS


[Display(Name = "Código do Cliente")]
        [Required(ErrorMessage = "Por Favor preencha o Código do Cliente")]
        private ushort CodCliente { get; set; }



        [Display(Name = "Nome do Cliente ")]
        [Required(ErrorMessage = "Por Favor preencha seu Nome")]
        private string Nome { get; set; }


        [Display(Name = "Endereço")]
        [Required(ErrorMessage = "Por Favor preencha seu Endereço")]
        private string Endereco { get; set; }



        [Display(Name = "Telefone")]
        [Required(ErrorMessage = "Digite seu Telefone")]
        [RegularExpression("^[0-9]{2}-([0-9]{8}|[0-9]{9})")]
         private string Telefone { get; set; }



         [Display(Name = "Email")]
         [RegularExpression(@"\w+([-+.']\w+)*@\w+([-.]\w+)*\.\w+([-.]\w+)*")]
         private string Email { get; set; }


         [Display(Name = "CPF")]
         [Required(ErrorMessage = " Preencha com seu CPF")]
         [StringLength(11)]
          private int CPF { get; set; }


         [Display(Name = "Data de Nascimento")]
         [Required(ErrorMessage = "Preencha com sua Data de Nascimento")]
         [DisplayFormat(DataFormatString = "{dd/mm/aaa}")]
         private DateTime DataNascimento { get; set; }








    }
}
