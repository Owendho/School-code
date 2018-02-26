# School-code
Code from school and home

using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace testingtesting
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void btnCompare_Click(object sender, EventArgs e)
        {
            int firstNumber;
            int secondnNumeber;

            firstNumber = int.Parse(txtBox1.Text);
            secondnNumeber = int.Parse(txtBox2.Text);

            if (firstNumber > secondnNumeber)
            {
                MessageBox.Show("Hello");
            }
            else
            {
                MessageBox.Show("fuk you");
            }

            
        }
    }
}
