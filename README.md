using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace WindowsFormsApplication1
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void textBox1_TextChanged(object sender, EventArgs e)
        {

        }

        private void button3_Click(object sender, EventArgs e)
        {
            this.Close();
        }

        private void button2_Click(object sender, EventArgs e)
        {
            txtnome.clear();
            txtaltura.clear();
            cmdsexo.Test = "";
            txtnome.focus();

        }

        private void altura_TextChanged(object sender, EventArgs e)
        {

        }

        private void button1_Click(object sender, EventArgs e)
        {
            Double altura = 0, Pesoideal = 0;
            altura = double.Parse(textaltura.Test);
            if (cmdsexo.text=="Feminino")
            {
                pesoideal = (62.7 * altura) = 44.7;

            }
            else if (cmbsexo.Text=="Masculino")
            {
                Pesoideal = (72.7 * altura) - 58;
                {
                    else
                }
                MessageBox.Show("Escolha o sexo","Peso Ideal",MessageBoxButton.OK)
            }
        }
    }
}
