# the-project

Microsoft Visual Studio Solution File, Format Version 12.00
# Visual Studio Version 16
VisualStudioVersion = 16.0.30204.135
MinimumVisualStudioVersion = 10.0.40219.1
Project("{FAE04EC0-301F-11D3-BF4B-00C04F79EFBC}") = "SmallStoreManagement", "SmallStoreManagement\SmallStoreManagement.csproj", "{4B8E30D9-C3D7-4E19-9A3B-CECA0D3D49B2}"
EndProject
Global
	GlobalSection(SolutionConfigurationPlatforms) = preSolution
		Debug|Any CPU = Debug|Any CPU
		Release|Any CPU = Release|Any CPU
	EndGlobalSection
	GlobalSection(ProjectConfigurationPlatforms) = postSolution
		{4B8E30D9-C3D7-4E19-9A3B-CECA0D3D49B2}.Debug|Any CPU.ActiveCfg = Debug|Any CPU
		{4B8E30D9-C3D7-4E19-9A3B-CECA0D3D49B2}.Debug|Any CPU.Build.0 = Debug|Any CPU
		{4B8E30D9-C3D7-4E19-9A3B-CECA0D3D49B2}.Release|Any CPU.ActiveCfg = Release|Any CPU
		{4B8E30D9-C3D7-4E19-9A3B-CECA0D3D49B2}.Release|Any CPU.Build.0 = Release|Any CPU
	EndGlobalSection
	GlobalSection(SolutionProperties) = preSolution
		HideSolutionNode = FALSE
	EndGlobalSection
	GlobalSection(ExtensibilityGlobals) = postSolution
		SolutionGuid = {6F47795E-7CBE-4A96-9FC7-B06411CFD15E}
	EndGlobalSection
EndGlobal

namespace SmallStoreManagement
{
    partial class AddCustomerForm
    {
        /// <summary>
        /// Required designer variable.
        /// </summary>
        private System.ComponentModel.IContainer components = null;

        /// <summary>
        /// Clean up any resources being used.
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
        /// Required method for Designer support - do not modify
        /// the contents of this method with the code editor.
        /// </summary>
        private void InitializeComponent()
        {
            this.CustomerNameLabel = new System.Windows.Forms.Label();
            this.CustomerAddressLabel = new System.Windows.Forms.Label();
            this.CustomerDiscountLabel = new System.Windows.Forms.Label();
            this.NewCustomerName = new System.Windows.Forms.TextBox();
            this.NewCustmomerAddress = new System.Windows.Forms.TextBox();
            this.NewCustomerDiscount = new System.Windows.Forms.TextBox();
            this.NewCustomerAddButton = new System.Windows.Forms.Button();
            this.CustomerPasswordLabel = new System.Windows.Forms.Label();
            this.NewCustomerPassword = new System.Windows.Forms.TextBox();
            this.SuspendLayout();
            // 
            // CustomerNameLabel
            // 
            this.CustomerNameLabel.AutoSize = true;
            this.CustomerNameLabel.Font = new System.Drawing.Font("Microsoft Sans Serif", 15.75F, System.Drawing.FontStyle.Regular, System.Drawing.GraphicsUnit.Point, ((byte)(0)));
            this.CustomerNameLabel.Location = new System.Drawing.Point(12, 9);
            this.CustomerNameLabel.Name = "CustomerNameLabel";
            this.CustomerNameLabel.Size = new System.Drawing.Size(166, 25);
            this.CustomerNameLabel.TabIndex = 4;
            this.CustomerNameLabel.Text = "Customer Name";
            // 
            // CustomerAddressLabel
            // 
            this.CustomerAddressLabel.AutoSize = true;
            this.CustomerAddressLabel.Font = new System.Drawing.Font("Microsoft Sans Serif", 15.75F, System.Drawing.FontStyle.Regular, System.Drawing.GraphicsUnit.Point, ((byte)(0)));
            this.CustomerAddressLabel.Location = new System.Drawing.Point(12, 62);
            this.CustomerAddressLabel.Name = "CustomerAddressLabel";
            this.CustomerAddressLabel.Size = new System.Drawing.Size(189, 25);
            this.CustomerAddressLabel.TabIndex = 5;
            this.CustomerAddressLabel.Text = "Customer Address";
            // 
            // CustomerDiscountLabel
            // 
            this.CustomerDiscountLabel.AutoSize = true;
            this.CustomerDiscountLabel.Font = new System.Drawing.Font("Microsoft Sans Serif", 15.75F, System.Drawing.FontStyle.Regular, System.Drawing.GraphicsUnit.Point, ((byte)(0)));
            this.CustomerDiscountLabel.Location = new System.Drawing.Point(12, 87);
            this.CustomerDiscountLabel.Name = "CustomerDiscountLabel";
            this.CustomerDiscountLabel.Size = new System.Drawing.Size(194, 25);
            this.CustomerDiscountLabel.TabIndex = 6;
            this.CustomerDiscountLabel.Text = "Customer Discount";
            // 
            // NewCustomerName
            // 
            this.NewCustomerName.Location = new System.Drawing.Point(219, 13);
            this.NewCustomerName.Name = "NewCustomerName";
            this.NewCustomerName.Size = new System.Drawing.Size(164, 20);
            this.NewCustomerName.TabIndex = 7;
            // 
            // NewCustmomerAddress
            // 
            this.NewCustmomerAddress.Location = new System.Drawing.Point(219, 62);
            this.NewCustmomerAddress.Name = "NewCustmomerAddress";
            this.NewCustmomerAddress.Size = new System.Drawing.Size(164, 20);
            this.NewCustmomerAddress.TabIndex = 8;
            // 
            // NewCustomerDiscount
            // 
            this.NewCustomerDiscount.Location = new System.Drawing.Point(219, 90);
            this.NewCustomerDiscount.Name = "NewCustomerDiscount";
            this.NewCustomerDiscount.Size = new System.Drawing.Size(164, 20);
            this.NewCustomerDiscount.TabIndex = 9;
            // 
            // NewCustomerAddButton
            // 
            this.NewCustomerAddButton.Font = new System.Drawing.Font("Microsoft Sans Serif", 24F, System.Drawing.FontStyle.Regular, System.Drawing.GraphicsUnit.Point, ((byte)(0)));
            this.NewCustomerAddButton.Location = new System.Drawing.Point(233, 119);
            this.NewCustomerAddButton.Name = "NewCustomerAddButton";
            this.NewCustomerAddButton.Size = new System.Drawing.Size(105, 43);
            this.NewCustomerAddButton.TabIndex = 10;
            this.NewCustomerAddButton.Text = "Add";
            this.NewCustomerAddButton.UseVisualStyleBackColor = true;
            this.NewCustomerAddButton.Click += new System.EventHandler(this.NewCustomerAddButton_Click);
            // 
            // CustomerPasswordLabel
            // 
            this.CustomerPasswordLabel.AutoSize = true;
            this.CustomerPasswordLabel.Font = new System.Drawing.Font("Microsoft Sans Serif", 15.75F, System.Drawing.FontStyle.Regular, System.Drawing.GraphicsUnit.Point, ((byte)(0)));
            this.CustomerPasswordLabel.Location = new System.Drawing.Point(12, 37);
            this.CustomerPasswordLabel.Name = "CustomerPasswordLabel";
            this.CustomerPasswordLabel.Size = new System.Drawing.Size(204, 25);
            this.CustomerPasswordLabel.TabIndex = 11;
            this.CustomerPasswordLabel.Text = "Customer Password";
            // 
            // NewCustomerPassword
            // 
            this.NewCustomerPassword.Location = new System.Drawing.Point(219, 39);
            this.NewCustomerPassword.Name = "NewCustomerPassword";
            this.NewCustomerPassword.Size = new System.Drawing.Size(164, 20);
            this.NewCustomerPassword.TabIndex = 12;
            // 
            // AddCustomerForm
            // 
            this.AutoScaleDimensions = new System.Drawing.SizeF(6F, 13F);
            this.AutoScaleMode = System.Windows.Forms.AutoScaleMode.Font;
            this.ClientSize = new System.Drawing.Size(395, 189);
            this.Controls.Add(this.NewCustomerPassword);
            this.Controls.Add(this.CustomerPasswordLabel);
            this.Controls.Add(this.NewCustomerAddButton);
            this.Controls.Add(this.NewCustomerDiscount);
            this.Controls.Add(this.NewCustmomerAddress);
            this.Controls.Add(this.NewCustomerName);
            this.Controls.Add(this.CustomerDiscountLabel);
            this.Controls.Add(this.CustomerAddressLabel);
            this.Controls.Add(this.CustomerNameLabel);
            this.Name = "AddCustomerForm";
            this.Text = "AddCustomerForm";
            this.ResumeLayout(false);
            this.PerformLayout();

        }

        #endregion

        private System.Windows.Forms.Label CustomerNameLabel;
        private System.Windows.Forms.Label CustomerAddressLabel;
        private System.Windows.Forms.Label CustomerDiscountLabel;
        private System.Windows.Forms.TextBox NewCustomerName;
        private System.Windows.Forms.TextBox NewCustmomerAddress;
        private System.Windows.Forms.TextBox NewCustomerDiscount;
        private System.Windows.Forms.Button NewCustomerAddButton;
        private System.Windows.Forms.Label CustomerPasswordLabel;
        private System.Windows.Forms.TextBox NewCustomerPassword;
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Security.Cryptography;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace SmallStoreManagement
{
    public partial class AddCustomerForm : Form
    {
        public AddCustomerForm()
        {
            InitializeComponent();
        }

        private void NewCustomerAddButton_Click(object sender, EventArgs e)
        {
            
            string userpasswordHash = Utils.CreateMD5(NewCustomerPassword.Text);

            Customer c = new Customer()
            {
                Fullname = NewCustomerName.Text,
                Password = userpasswordHash,
                Address  = NewCustmomerAddress.Text,
                Discount = Int32.Parse(NewCustomerDiscount.Text)
            };
            Customer.AddCustomer(c);
            this.Close();
        }
    }
}
<?xml version="1.0" encoding="utf-8"?>
<root>
  <!-- 
    Microsoft ResX Schema 
    
    Version 2.0
    
    The primary goals of this format is to allow a simple XML format 
    that is mostly human readable. The generation and parsing of the 
    various data types are done through the TypeConverter classes 
    associated with the data types.
    
    Example:
    
    ... ado.net/XML headers & schema ...
    <resheader name="resmimetype">text/microsoft-resx</resheader>
    <resheader name="version">2.0</resheader>
    <resheader name="reader">System.Resources.ResXResourceReader, System.Windows.Forms, ...</resheader>
    <resheader name="writer">System.Resources.ResXResourceWriter, System.Windows.Forms, ...</resheader>
    <data name="Name1"><value>this is my long string</value><comment>this is a comment</comment></data>
    <data name="Color1" type="System.Drawing.Color, System.Drawing">Blue</data>
    <data name="Bitmap1" mimetype="application/x-microsoft.net.object.binary.base64">
        <value>[base64 mime encoded serialized .NET Framework object]</value>
    </data>
    <data name="Icon1" type="System.Drawing.Icon, System.Drawing" mimetype="application/x-microsoft.net.object.bytearray.base64">
        <value>[base64 mime encoded string representing a byte array form of the .NET Framework object]</value>
        <comment>This is a comment</comment>
    </data>
                
    There are any number of "resheader" rows that contain simple 
    name/value pairs.
    
    Each data row contains a name, and value. The row also contains a 
    type or mimetype. Type corresponds to a .NET class that support 
    text/value conversion through the TypeConverter architecture. 
    Classes that don't support this are serialized and stored with the 
    mimetype set.
    
    The mimetype is used for serialized objects, and tells the 
    ResXResourceReader how to depersist the object. This is currently not 
    extensible. For a given mimetype the value must be set accordingly:
    
    Note - application/x-microsoft.net.object.binary.base64 is the format 
    that the ResXResourceWriter will generate, however the reader can 
    read any of the formats listed below.
    
    mimetype: application/x-microsoft.net.object.binary.base64
    value   : The object must be serialized with 
            : System.Runtime.Serialization.Formatters.Binary.BinaryFormatter
            : and then encoded with base64 encoding.
    
    mimetype: application/x-microsoft.net.object.soap.base64
    value   : The object must be serialized with 
            : System.Runtime.Serialization.Formatters.Soap.SoapFormatter
            : and then encoded with base64 encoding.
    mimetype: application/x-microsoft.net.object.bytearray.base64
    value   : The object must be serialized into a byte array 
            : using a System.ComponentModel.TypeConverter
            : and then encoded with base64 encoding.
    -->
  <xsd:schema id="root" xmlns="" xmlns:xsd="http://www.w3.org/2001/XMLSchema" xmlns:msdata="urn:schemas-microsoft-com:xml-msdata">
    <xsd:import namespace="http://www.w3.org/XML/1998/namespace" />
    <xsd:element name="root" msdata:IsDataSet="true">
      <xsd:complexType>
        <xsd:choice maxOccurs="unbounded">
          <xsd:element name="metadata">
            <xsd:complexType>
              <xsd:sequence>
                <xsd:element name="value" type="xsd:string" minOccurs="0" />
              </xsd:sequence>
              <xsd:attribute name="name" use="required" type="xsd:string" />
              <xsd:attribute name="type" type="xsd:string" />
              <xsd:attribute name="mimetype" type="xsd:string" />
              <xsd:attribute ref="xml:space" />
            </xsd:complexType>
          </xsd:element>
          <xsd:element name="assembly">
            <xsd:complexType>
              <xsd:attribute name="alias" type="xsd:string" />
              <xsd:attribute name="name" type="xsd:string" />
            </xsd:complexType>
          </xsd:element>
          <xsd:element name="data">
            <xsd:complexType>
              <xsd:sequence>
                <xsd:element name="value" type="xsd:string" minOccurs="0" msdata:Ordinal="1" />
                <xsd:element name="comment" type="xsd:string" minOccurs="0" msdata:Ordinal="2" />
              </xsd:sequence>
              <xsd:attribute name="name" type="xsd:string" use="required" msdata:Ordinal="1" />
              <xsd:attribute name="type" type="xsd:string" msdata:Ordinal="3" />
              <xsd:attribute name="mimetype" type="xsd:string" msdata:Ordinal="4" />
              <xsd:attribute ref="xml:space" />
            </xsd:complexType>
          </xsd:element>
          <xsd:element name="resheader">
            <xsd:complexType>
              <xsd:sequence>
                <xsd:element name="value" type="xsd:string" minOccurs="0" msdata:Ordinal="1" />
              </xsd:sequence>
              <xsd:attribute name="name" type="xsd:string" use="required" />
            </xsd:complexType>
          </xsd:element>
        </xsd:choice>
      </xsd:complexType>
    </xsd:element>
  </xsd:schema>
  <resheader name="resmimetype">
    <value>text/microsoft-resx</value>
  </resheader>
  <resheader name="version">
    <value>2.0</value>
  </resheader>
  <resheader name="reader">
    <value>System.Resources.ResXResourceReader, System.Windows.Forms, Version=4.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089</value>
  </resheader>
  <resheader name="writer">
    <value>System.Resources.ResXResourceWriter, System.Windows.Forms, Version=4.0.0.0, Culture=neutral, PublicKeyToken=b77a5c561934e089</value>
  </resheader>
</root>

using System;
using System.Collections.Generic;
using System.Data.SQLite;

namespace SmallStoreManagement
{
    public class Product
    {
        private static readonly string cs = @"URI = file:SmallStoreManagement.db";

        public string ProductName { get; set; }
        public string Category { get; set; }
        public int Price { get; set; }
        public int Id { get; set; }

        public static List<Product> GetAllProducts()
        {
            List<Product> result = new List<Product>();
            string stm = "SELECT Id, ProductName, Category, Price FROM Products";
            using (SQLiteConnection con = new SQLiteConnection(cs))
            {
                con.Open();
                using (SQLiteCommand cmd = new SQLiteCommand(stm, con))
                {
                    using (SQLiteDataReader reader = cmd.ExecuteReader())
                    {
                        while (reader.Read())
                        {
                            result.Add(new Product()
                            {
                                Id = reader.GetInt32(0),
                                ProductName = reader.GetString(1),
                                Category = reader.GetString(2),
                                Price = reader.GetInt32(3)
                            });
                        }
                    }
                }
                con.Close();
            }
            return result;
        }
        public static void AddProduct(Product p)
        {

            using (SQLiteConnection con = new SQLiteConnection(cs))
            {
                string stm = "INSERT INTO Products (ProductName, Category, Price) VALUES (@ProductName, @Category, @Price);";
                SQLiteCommand cmd = new SQLiteCommand(stm, con);

                cmd.Parameters.AddWithValue("@ProductName", p.ProductName);
                cmd.Parameters.AddWithValue("@Category", p.Category);
                cmd.Parameters.AddWithValue("@Price", p.Price);

                con.Open();
                cmd.ExecuteNonQuery();
                con.Close();
            }

        }

    }
}

