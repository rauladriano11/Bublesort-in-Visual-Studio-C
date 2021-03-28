
namespace Ordenamiento_de_Burbuja
{
    
    public partial class Form1 : Form
    {
        List<int> numeros1 = new List<int>();
        public Form1()
        {
            InitializeComponent();
        }

        private void Form1_Load(object sender, EventArgs e)
        {

        }

        private void button1_Click(object sender, EventArgs e)
        {
            // Agregar un numero a la lista lstOriginal
            // Declarar variable
            int nro;
            // Leer el numero de txtNro
            nro = int.Parse(txtNro.Text);
            // Llevar el numero a la lista lstOriginal
            lstOriginal.Items.Add(nro);
            // Limpiar la caja de Texto txtNro
            txtNro.Clear();
            txtNro.Focus();
            numeros1.Add(nro);
            //int[] numeros = numeros1.ToArray();

        }
        
        private void btnOrdenar_Click(object sender, EventArgs e)
        {
            //int[] arreglo = new int[] { 5, 8, 4, 6, 7, 1 };
            //int[] numeros = new int[] { };
            int[] numeros = numeros1.ToArray();
            int i, j;
            int aux;
            for (i = 0; i < numeros.Length; i++)
            {
                for (j = 0; j < i; j++)
                {
                    if (numeros[i] < numeros[j])
                    {
                        aux = numeros[j];
                        numeros[j] = numeros[i];
                        numeros[i] = aux;
                    }
                }
            }
            //Arreglo Ordenado 
            foreach (var item in numeros)
            {
                lstOrdenada.Items.Add(item.ToString());
            }
        }

        private void lstOrdenada_SelectedIndexChanged(object sender, EventArgs e)
        {

        }
        private void lstOriginal_SelectedIndexChanged(object sender, EventArgs e)
        {
            
        }
        private void txtNro_TextChanged(object sender, EventArgs e)
        {

        }
    }
}
