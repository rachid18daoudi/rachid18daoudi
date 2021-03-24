            string genre;
            if (rbf.Checked)
                genre = "F";
            else
                genre = "M";


            dataGridView1.Rows.Add(txtnom.Text, txtprenom.Text, mtxtdate.Text, genre,comboBox1.SelectedItem.ToString());

            ListViewItem i = new ListViewItem();
            i.Text = (txtnom.Text);
            i.SubItems.Add(txtprenom.Text);
            i.SubItems.Add(mtxtdate.Text);
            i.SubItems.Add(comboBox1.SelectedItem.ToString());
            i.SubItems.Add(genre);
            listView1.Items.A
