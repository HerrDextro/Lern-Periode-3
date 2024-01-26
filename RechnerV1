FORM1.CS------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

namespace RechnerV1
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        string CalTotal;
        int num1;
        int num2;
        string option;
        int result;



        private void button1_Click(object sender, EventArgs e)
        {
            textBox1.Text = textBox1.Text + "1";
        }

        private void button2_Click(object sender, EventArgs e)
        {
            textBox1.Text = textBox1.Text + "2";
        }

        private void button3_Click(object sender, EventArgs e)
        {
            textBox1.Text = textBox1.Text + "3";
        }

        private void button5_Click(object sender, EventArgs e)
        {
            textBox1.Text = textBox1.Text + "4";
        }

        private void button4_Click(object sender, EventArgs e)
        {
            textBox1.Text = textBox1.Text + "5";
        }

        private void button10_Click(object sender, EventArgs e)
        {
            textBox1.Text = textBox1.Text + "6";
        }

        private void button9_Click(object sender, EventArgs e)
        {
            textBox1.Text = textBox1.Text + "7";
        }

        private void button8_Click(object sender, EventArgs e)
        {
            textBox1.Text = textBox1.Text + "8";
        }

        private void button6_Click(object sender, EventArgs e)
        {
            textBox1.Text = textBox1.Text + "9";
        }

        private void button7_Click(object sender, EventArgs e)
        {
            textBox1.Text = textBox1.Text + "0";
        }

        private void button15_Click(object sender, EventArgs e)
        {
            option = "+";
            num1 = int.Parse(textBox1.Text);
            textBox1.Clear();

        }

        private void button14_Click(object sender, EventArgs e)
        {
            option = "-";
            num1 = int.Parse(textBox1.Text);
            textBox1.Clear();
        }

        private void button13_Click(object sender, EventArgs e)
        {
            option = "*";
            num1 = int.Parse(textBox1.Text);
            textBox1.Clear();
        }

        private void button11_Click(object sender, EventArgs e)
        {
            option = "/";
            num1 = int.Parse(textBox1.Text);
            textBox1.Clear();
        }

        private void button16_Click(object sender, EventArgs e)
        {
            num2 = int.Parse(textBox1.Text);

            if (option.Equals("+"))
                result = num1 + num2;

            if (option.Equals("-"))
                result = num1 - num2;

            if (option.Equals("*"))
                result = num1 * num2;

            if (option.Equals("/"))
                result = num1 / num2;

            textBox1.Text = result + " ";


        }

        private void button12_Click(object sender, EventArgs e)
        {
            textBox1.Clear();
            result = 0;
            num1 = 0;
            num2 = 0;
        }
    }
}


FORM1.DESIGNER.CS----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
namespace RechnerV1
{
    partial class Form1
    {
        /// <summary>
        ///  Required designer variable.
        /// </summary>
        private System.ComponentModel.IContainer components = null;

        /// <summary>
        ///  Clean up any resources being used.
        /// </summary>
        /// <param name="disposing">true if managed resources should be disposed; otherwise, false.</param>
        protected override void Dispose(bool disposing)
        {
            if (disposing && (components != null))
            {
                components.Dispose();
            }
            base.Dispose(disposing);
        }

        #region Windows Form Designer generated code

        /// <summary>
        ///  Required method for Designer support - do not modify
        ///  the contents of this method with the code editor.
        /// </summary>
        private void InitializeComponent()
        {
            textBox1 = new TextBox();
            button1 = new Button();
            button2 = new Button();
            button3 = new Button();
            button4 = new Button();
            button5 = new Button();
            button6 = new Button();
            button7 = new Button();
            button8 = new Button();
            button9 = new Button();
            button10 = new Button();
            button11 = new Button();
            button12 = new Button();
            button13 = new Button();
            button14 = new Button();
            button15 = new Button();
            button16 = new Button();
            SuspendLayout();
            // 
            // textBox1
            // 
            textBox1.Font = new Font("Times New Roman", 24F, FontStyle.Bold);
            textBox1.Location = new Point(71, 37);
            textBox1.Multiline = true;
            textBox1.Name = "textBox1";
            textBox1.Size = new Size(644, 124);
            textBox1.TabIndex = 0;
            // 
            // button1
            // 
            button1.Font = new Font("Segoe UI", 12F, FontStyle.Bold);
            button1.Location = new Point(71, 178);
            button1.Name = "button1";
            button1.Size = new Size(114, 86);
            button1.TabIndex = 1;
            button1.Text = "1";
            button1.UseVisualStyleBackColor = true;
            button1.Click += button1_Click;
            // 
            // button2
            // 
            button2.Font = new Font("Segoe UI", 12F, FontStyle.Bold);
            button2.Location = new Point(205, 178);
            button2.Name = "button2";
            button2.Size = new Size(114, 86);
            button2.TabIndex = 2;
            button2.Text = "2";
            button2.UseVisualStyleBackColor = true;
            button2.Click += button2_Click;
            // 
            // button3
            // 
            button3.Font = new Font("Segoe UI", 12F, FontStyle.Bold);
            button3.Location = new Point(337, 178);
            button3.Name = "button3";
            button3.Size = new Size(114, 86);
            button3.TabIndex = 3;
            button3.Text = "3";
            button3.UseVisualStyleBackColor = true;
            button3.Click += button3_Click;
            // 
            // button4
            // 
            button4.Font = new Font("Segoe UI", 12F, FontStyle.Bold);
            button4.Location = new Point(601, 178);
            button4.Name = "button4";
            button4.Size = new Size(114, 86);
            button4.TabIndex = 4;
            button4.Text = "5";
            button4.UseVisualStyleBackColor = true;
            button4.Click += button4_Click;
            // 
            // button5
            // 
            button5.Font = new Font("Segoe UI", 12F, FontStyle.Bold);
            button5.Location = new Point(469, 178);
            button5.Name = "button5";
            button5.Size = new Size(114, 86);
            button5.TabIndex = 5;
            button5.Text = "4";
            button5.UseVisualStyleBackColor = true;
            button5.Click += button5_Click;
            // 
            // button6
            // 
            button6.Font = new Font("Segoe UI", 12F, FontStyle.Bold);
            button6.Location = new Point(469, 270);
            button6.Name = "button6";
            button6.Size = new Size(114, 86);
            button6.TabIndex = 10;
            button6.Text = "9";
            button6.UseVisualStyleBackColor = true;
            button6.Click += button6_Click;
            // 
            // button7
            // 
            button7.Font = new Font("Segoe UI", 12F, FontStyle.Bold);
            button7.Location = new Point(601, 270);
            button7.Name = "button7";
            button7.Size = new Size(114, 86);
            button7.TabIndex = 9;
            button7.Text = "0";
            button7.UseVisualStyleBackColor = true;
            button7.Click += button7_Click;
            // 
            // button8
            // 
            button8.Font = new Font("Segoe UI", 12F, FontStyle.Bold);
            button8.Location = new Point(337, 270);
            button8.Name = "button8";
            button8.Size = new Size(114, 86);
            button8.TabIndex = 8;
            button8.Text = "8";
            button8.UseVisualStyleBackColor = true;
            button8.Click += button8_Click;
            // 
            // button9
            // 
            button9.Font = new Font("Segoe UI", 12F, FontStyle.Bold);
            button9.Location = new Point(205, 270);
            button9.Name = "button9";
            button9.Size = new Size(114, 86);
            button9.TabIndex = 7;
            button9.Text = "7";
            button9.UseVisualStyleBackColor = true;
            button9.Click += button9_Click;
            // 
            // button10
            // 
            button10.Font = new Font("Segoe UI", 12F, FontStyle.Bold);
            button10.Location = new Point(71, 270);
            button10.Name = "button10";
            button10.Size = new Size(114, 86);
            button10.TabIndex = 6;
            button10.Text = "6";
            button10.UseVisualStyleBackColor = true;
            button10.Click += button10_Click;
            // 
            // button11
            // 
            button11.Font = new Font("Segoe UI", 12F, FontStyle.Bold);
            button11.Location = new Point(469, 362);
            button11.Name = "button11";
            button11.Size = new Size(114, 86);
            button11.TabIndex = 15;
            button11.Text = "/";
            button11.UseVisualStyleBackColor = true;
            button11.Click += button11_Click;
            // 
            // button12
            // 
            button12.Font = new Font("Segoe UI", 12F, FontStyle.Bold);
            button12.Location = new Point(601, 362);
            button12.Name = "button12";
            button12.Size = new Size(114, 86);
            button12.TabIndex = 14;
            button12.Text = "Clear";
            button12.UseVisualStyleBackColor = true;
            button12.Click += button12_Click;
            // 
            // button13
            // 
            button13.Font = new Font("Segoe UI", 12F, FontStyle.Bold);
            button13.Location = new Point(337, 362);
            button13.Name = "button13";
            button13.Size = new Size(114, 86);
            button13.TabIndex = 13;
            button13.Text = "*";
            button13.UseVisualStyleBackColor = true;
            button13.Click += button13_Click;
            // 
            // button14
            // 
            button14.Font = new Font("Segoe UI", 12F, FontStyle.Bold);
            button14.Location = new Point(205, 362);
            button14.Name = "button14";
            button14.Size = new Size(114, 86);
            button14.TabIndex = 12;
            button14.Text = "-";
            button14.UseVisualStyleBackColor = true;
            button14.Click += button14_Click;
            // 
            // button15
            // 
            button15.Font = new Font("Segoe UI", 12F, FontStyle.Bold);
            button15.Location = new Point(71, 362);
            button15.Name = "button15";
            button15.Size = new Size(114, 86);
            button15.TabIndex = 11;
            button15.Text = "+";
            button15.UseVisualStyleBackColor = true;
            button15.Click += button15_Click;
            // 
            // button16
            // 
            button16.Font = new Font("Segoe UI", 12F, FontStyle.Bold);
            button16.Location = new Point(469, 454);
            button16.Name = "button16";
            button16.Size = new Size(246, 86);
            button16.TabIndex = 16;
            button16.Text = "=";
            button16.UseVisualStyleBackColor = true;
            button16.Click += button16_Click;
            // 
            // Form1
            // 
            AutoScaleDimensions = new SizeF(8F, 20F);
            AutoScaleMode = AutoScaleMode.Font;
            ClientSize = new Size(800, 579);
            Controls.Add(button16);
            Controls.Add(button11);
            Controls.Add(button12);
            Controls.Add(button13);
            Controls.Add(button14);
            Controls.Add(button15);
            Controls.Add(button6);
            Controls.Add(button7);
            Controls.Add(button8);
            Controls.Add(button9);
            Controls.Add(button10);
            Controls.Add(button5);
            Controls.Add(button4);
            Controls.Add(button3);
            Controls.Add(button2);
            Controls.Add(button1);
            Controls.Add(textBox1);
            Name = "Form1";
            StartPosition = FormStartPosition.CenterScreen;
            Text = "RechnerV1";
            ResumeLayout(false);
            PerformLayout();
        }

        #endregion

        private TextBox textBox1;
        private Button button1;
        private Button button2;
        private Button button3;
        private Button button4;
        private Button button5;
        private Button button6;
        private Button button7;
        private Button button8;
        private Button button9;
        private Button button10;
        private Button button11;
        private Button button12;
        private Button button13;
        private Button button14;
        private Button button15;
        private Button button16;
    }
}
