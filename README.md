# Activity-1
namespace WelcomeFormApp
{
    partial class Form1
    {
        private System.ComponentModel.IContainer components = null;

        protected override void Dispose(bool disposing)
        {
            if (disposing && (components != null))
            {
                components.Dispose();
            }
            base.Dispose(disposing);
        }

        private void InitializeComponent()
        {
            this.labelPrompt = new System.Windows.Forms.Label();
            this.textBoxName = new System.Windows.Forms.TextBox();
            this.buttonGreet = new System.Windows.Forms.Button();
            this.labelMessage = new System.Windows.Forms.Label();
            this.SuspendLayout();
           
            this.labelPrompt.AutoSize = true;
            this.labelPrompt.Location = new System.Drawing.Point(13, 13);
            this.labelPrompt.Name = "labelPrompt";
            this.labelPrompt.Size = new System.Drawing.Size(92, 13);
            this.labelPrompt.TabIndex = 0;
            this.labelPrompt.Text = "Enter your name:";
     
            this.textBoxName.Location = new System.Drawing.Point(16, 30);
            this.textBoxName.Name = "textBoxName";
            this.textBoxName.Size = new System.Drawing.Size(200, 20);
            this.textBoxName.TabIndex = 1;
           
            this.buttonGreet.Location = new System.Drawing.Point(16, 57);
            this.buttonGreet.Name = "buttonGreet";
            this.buttonGreet.Size = new System.Drawing.Size(75, 23);
            this.buttonGreet.TabIndex = 2;
            this.buttonGreet.Text = "Greet Me";
            this.buttonGreet.UseVisualStyleBackColor = true;
            this.buttonGreet.Click += new System.EventHandler(this.buttonGreet_Click);
            
            this.labelMessage.AutoSize = true;
            this.labelMessage.Location = new System.Drawing.Point(16, 87);
            this.labelMessage.Name = "labelMessage";
            this.labelMessage.Size = new System.Drawing.Size(0, 13);
            this.labelMessage.TabIndex = 3;
           
            this.AutoScaleDimensions = new System.Drawing.SizeF(6F, 13F);
            this.AutoScaleMode = System.Windows.Forms.AutoScaleMode.Font;
            this.ClientSize = new System.Drawing.Size(284, 131);
            this.Controls.Add(this.labelMessage);
            this.Controls.Add(this.buttonGreet);
            this.Controls.Add(this.textBoxName);
            this.Controls.Add(this.labelPrompt);
            this.Name = "Form1";
            this.Text = "Welcome Form";
            this.ResumeLayout(false);
            this.PerformLayout();
        }

        private System.Windows.Forms.Label labelPrompt;
        private System.Windows.Forms.TextBox textBoxName;
        private System.Windows.Forms.Button buttonGreet;
        private System.Windows.Forms.Label labelMessage;
    }
}
