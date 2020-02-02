# Prezzo-scontato
Sconto di qualsiasi prodotto
Public Class Form1
    Private Sub btnCalc_Click(sender As Object, e As EventArgs) Handles btnCalc.Click
        Dim intNum1 As Double
        Dim intNum2 As Double
        Dim intAnswer As Double
        Dim risparmio1 As Double
        Dim quantità1 As Integer
        Dim totale1 As Double
        Double.TryParse(txtNum1.Text, intNum1)
        Double.TryParse(txtNum2.Text, intNum2)
        Double.TryParse(txttotale1.Text, totale1)
        Double.TryParse(txtintAnswer.Text, intAnswer)
        Double.TryParse(txtrisparmio1.Text, risparmio1)
        Integer.TryParse(txtquantità1.Text, quantità1)

        If chkMoltiplicazione.Checked = True Then
            intAnswer = (intNum1 * quantità1) - (intNum1 * quantità1) * intNum2 / 100
            risparmio1 = (intNum1 * quantità1) * intNum2 / 100
            totale1 = intNum1 * quantità1
            lbltotale1.Text = totale1.ToString("C2")
            lblrisparmio1.Text = risparmio1.ToString("C2")
            lblAnswer.Text = intAnswer.ToString("C2")
            txttotale1.Text = (intNum1 * quantità1).ToString("C2")
            txtintAnswer.Text = ((intNum1 * quantità1) - (intNum1 * quantità1) * intNum2 / 100).ToString("C2")
            txtrisparmio1.Text = ((intNum1 * quantità1) * intNum2 / 100).ToString("C2")
        End If

        Dim intNum3 As Double
        Dim intNum4 As Double
        Dim intAnswer1 As Double
        Dim risparmio2 As Double
        Dim quantità2 As Integer
        Dim totale2 As Double
        Double.TryParse(txtNum3.Text, intNum3)
        Double.TryParse(txtNum4.Text, intNum4)
        Double.TryParse(txttotale2.Text, totale2)
        Double.TryParse(txtintAnswer1.Text, intAnswer1)
        Double.TryParse(txtrisparmio2.Text, risparmio2)
        Integer.TryParse(txtquantità2.Text, quantità2)

        If chkMoltiplicazione1.Checked = True Then
            intAnswer1 = (intNum3 * quantità2) - (intNum3 * quantità2) * intNum4 / 100
            risparmio2 = (intNum3 * quantità2) * intNum4 / 100
            totale2 = intNum3 * quantità2
            lbltotale2.Text = totale2.ToString("C2")
            lblrisparmio2.Text = risparmio2.ToString("C2")
            lblAnswer1.Text = intAnswer1.ToString("C2")
            txttotale2.Text = (intNum3 * quantità2).ToString("C2")
            txtintAnswer1.Text = ((intNum3 * quantità2) - (intNum3 * quantità2) * intNum4 / 100).ToString("C2")
            txtrisparmio2.Text = ((intNum3 * quantità2) * intNum4 / 100).ToString("C2")
        End If

        Dim intNum5 As Double
        Dim intNum6 As Double
        Dim intAnswer2 As Double
        Dim risparmio3 As Double
        Dim quantità3 As Integer
        Dim totale3 As Double
        Double.TryParse(txtNum5.Text, intNum5)
        Double.TryParse(txtNum6.Text, intNum6)
        Double.TryParse(txttotale3.Text, totale3)
        Double.TryParse(txtintAnswer2.Text, intAnswer2)
        Double.TryParse(txtrisparmio3.Text, risparmio3)
        Integer.TryParse(txtquantità3.Text, quantità3)

        If chkMoltiplicazione2.Checked = True Then
            intAnswer2 = (intNum5 * quantità3) - (intNum5 * quantità3) * intNum6 / 100
            risparmio3 = (intNum5 * quantità3) * intNum6 / 100
            totale3 = intNum5 * quantità3
            lbltotale3.Text = totale3.ToString("C2")
            lblrisparmio3.Text = risparmio3.ToString("C2")
            lblAnswer2.Text = intAnswer2.ToString("C2")
            txttotale3.Text = (intNum5 * quantità3).ToString("C2")
            txtintAnswer2.Text = ((intNum5 * quantità3) - (intNum5 * quantità3) * intNum6 / 100).ToString("C2")
            txtrisparmio3.Text = ((intNum5 * quantità3) * intNum6 / 100).ToString("C2")
        End If

        Dim intNum7 As Double
        Dim intNum8 As Double
        Dim intAnswer3 As Double
        Dim risparmio4 As Double
        Dim quantità4 As Integer
        Dim totale4 As Double
        Double.TryParse(txtNum7.Text, intNum7)
        Double.TryParse(txtNum8.Text, intNum8)
        Double.TryParse(txttotale4.Text, totale4)
        Double.TryParse(txtintAnswer3.Text, intAnswer3)
        Double.TryParse(txtrisparmio4.Text, risparmio4)
        Integer.TryParse(txtquantità4.Text, quantità4)

        If chkMoltiplicazione3.Checked = True Then
            intAnswer3 = (intNum7 * quantità4) - (intNum7 * quantità4) * intNum8 / 100
            risparmio4 = (intNum7 * quantità4) * intNum8 / 100
            totale4 = intNum7 * quantità4
            lbltotale4.Text = totale4.ToString("C2")
            lblrisparmio4.Text = risparmio4.ToString("C2")
            lblAnswer3.Text = intAnswer3.ToString("C2")
            txttotale4.Text = (intNum7 * quantità4).ToString("C2")
            txtintAnswer3.Text = ((intNum7 * quantità4) - (intNum7 * quantità4) * intNum8 / 100).ToString("C2")
            txtrisparmio4.Text = ((intNum7 * quantità4) * intNum8 / 100).ToString("C2")
        End If

        Dim intNum9 As Double
        Dim intNum10 As Double
        Dim intAnswer4 As Double
        Dim risparmio5 As Double
        Dim quantità5 As Integer
        Dim totale5 As Double
        Double.TryParse(txtNum9.Text, intNum9)
        Double.TryParse(txtNum10.Text, intNum10)
        Double.TryParse(txttotale5.Text, totale5)
        Double.TryParse(txtintAnswer4.Text, intAnswer4)
        Double.TryParse(txtrisparmio5.Text, risparmio5)
        Integer.TryParse(txtquantità5.Text, quantità5)

        If chkMoltiplicazione4.Checked = True Then
            intAnswer4 = (intNum9 * quantità5) - (intNum9 * quantità5) * intNum10 / 100
            risparmio5 = (intNum9 * quantità5) * intNum10 / 100
            totale5 = intNum9 * quantità5
            lbltotale5.Text = totale5.ToString("C2")
            lblrisparmio5.Text = risparmio5.ToString("C2")
            lblAnswer4.Text = intAnswer4.ToString("C2")
            txttotale5.Text = (intNum9 * quantità5).ToString("C2")
            txtintAnswer4.Text = ((intNum9 * quantità5) - (intNum9 * quantità5) * intNum10 / 100).ToString("C2")
            txtrisparmio5.Text = ((intNum9 * quantità5) * intNum10 / 100).ToString("C2")
        End If

        Dim intNum11 As Double
        Dim intNum12 As Double
        Dim intAnswer5 As Double
        Dim risparmio6 As Double
        Dim quantità6 As Integer
        Dim totale6 As Double
        Double.TryParse(txtNum11.Text, intNum11)
        Double.TryParse(txtNum12.Text, intNum12)
        Double.TryParse(txttotale6.Text, totale6)
        Double.TryParse(txtintAnswer5.Text, intAnswer5)
        Double.TryParse(txtrisparmio6.Text, risparmio6)
        Integer.TryParse(txtquantità6.Text, quantità6)

        If chkMoltiplicazione5.Checked = True Then
            intAnswer5 = (intNum11 * quantità6) - (intNum11 * quantità6) * intNum12 / 100
            risparmio6 = (intNum11 * quantità6) * intNum12 / 100
            totale6 = intNum11 * quantità6
            lbltotale6.Text = totale6.ToString("C2")
            lblrisparmio6.Text = risparmio6.ToString("C2")
            lblAnswer5.Text = intAnswer5.ToString("C2")
            txttotale6.Text = (intNum11 * quantità6).ToString("C2")
            txtintAnswer5.Text = ((intNum11 * quantità6) - (intNum11 * quantità6) * intNum12 / 100).ToString("C2")
            txtrisparmio6.Text = ((intNum11 * quantità6) * intNum12 / 100).ToString("C2")
        End If

        Dim intNum13 As Double
        Dim intNum14 As Double
        Dim intAnswer6 As Double
        Dim risparmio7 As Double
        Dim quantità7 As Integer
        Dim totale7 As Double
        Double.TryParse(txtNum13.Text, intNum13)
        Double.TryParse(txtNum14.Text, intNum14)
        Double.TryParse(txttotale7.Text, totale7)
        Double.TryParse(txtintAnswer6.Text, intAnswer6)
        Double.TryParse(txtrisparmio7.Text, risparmio7)
        Integer.TryParse(txtquantità7.Text, quantità7)

        If chkMoltiplicazione6.Checked = True Then
            intAnswer6 = (intNum13 * quantità7) - (intNum13 * quantità7) * intNum14 / 100
            risparmio7 = (intNum13 * quantità7) * intNum14 / 100
            totale7 = intNum13 * quantità7
            lbltotale7.Text = totale7.ToString("C2")
            lblrisparmio7.Text = risparmio7.ToString("C2")
            lblAnswer6.Text = intAnswer6.ToString("C2")
            txttotale7.Text = (intNum13 * quantità7).ToString("C2")
            txtintAnswer6.Text = ((intNum13 * quantità7) - (intNum13 * quantità7) * intNum14 / 100).ToString("C2")
            txtrisparmio7.Text = ((intNum13 * quantità7) * intNum14 / 100).ToString("C2")
        End If

        Dim intNum15 As Double
        Dim intNum16 As Double
        Dim intAnswer7 As Double
        Dim risparmio8 As Double
        Dim quantità8 As Integer
        Dim totale8 As Double
        Double.TryParse(txtNum15.Text, intNum15)
        Double.TryParse(txtNum16.Text, intNum16)
        Double.TryParse(txttotale8.Text, totale8)
        Double.TryParse(txtintAnswer7.Text, intAnswer7)
        Double.TryParse(txtrisparmio8.Text, risparmio8)
        Integer.TryParse(txtquantità8.Text, quantità8)

        If chkMoltiplicazione7.Checked = True Then
            intAnswer7 = (intNum15 * quantità8) - (intNum15 * quantità8) * intNum16 / 100
            risparmio8 = (intNum15 * quantità8) * intNum16 / 100
            totale8 = intNum15 * quantità8
            lbltotale8.Text = totale8.ToString("C2")
            lblrisparmio8.Text = risparmio8.ToString("C2")
            lblAnswer7.Text = intAnswer7.ToString("C2")
            txttotale8.Text = (intNum15 * quantità8).ToString("C2")
            txtintAnswer7.Text = ((intNum15 * quantità8) - (intNum15 * quantità8) * intNum16 / 100).ToString("C2")
            txtrisparmio8.Text = ((intNum15 * quantità8) * intNum16 / 100).ToString("C2")
        End If

        Dim intNum17 As Double
        Dim intNum18 As Double
        Dim intAnswer8 As Double
        Dim risparmio9 As Double
        Dim quantità9 As Integer
        Dim totale9 As Double
        Double.TryParse(txtNum17.Text, intNum17)
        Double.TryParse(txtNum18.Text, intNum18)
        Double.TryParse(txttotale9.Text, totale9)
        Double.TryParse(txtintAnswer8.Text, intAnswer8)
        Double.TryParse(txtrisparmio9.Text, risparmio9)
        Integer.TryParse(txtquantità9.Text, quantità9)

        If chkMoltiplicazione8.Checked = True Then
            intAnswer8 = (intNum17 * quantità9) - (intNum17 * quantità9) * intNum18 / 100
            risparmio9 = (intNum17 * quantità9) * intNum18 / 100
            totale9 = intNum17 * quantità9
            lbltotale9.Text = totale9.ToString("C2")
            lblrisparmio9.Text = risparmio9.ToString("C2")
            lblAnswer8.Text = intAnswer8.ToString("C2")
            txttotale9.Text = (intNum17 * quantità9).ToString("C2")
            txtintAnswer8.Text = ((intNum17 * quantità9) - (intNum17 * quantità9) * intNum18 / 100).ToString("C2")
            txtrisparmio9.Text = ((intNum17 * quantità9) * intNum18 / 100).ToString("C2")
        End If

        Dim intNum19 As Double
        Dim intNum20 As Double
        Dim intAnswer9 As Double
        Dim risparmio10 As Double
        Dim quantità10 As Integer
        Dim totale10 As Double
        Double.TryParse(txtNum19.Text, intNum19)
        Double.TryParse(txtNum20.Text, intNum20)
        Double.TryParse(txttotale10.Text, totale10)
        Double.TryParse(txtintAnswer9.Text, intAnswer9)
        Double.TryParse(txtrisparmio10.Text, risparmio10)
        Integer.TryParse(txtquantità10.Text, quantità10)

        If chkMoltiplicazione9.Checked = True Then
            intAnswer9 = (intNum19 * quantità10) - (intNum19 * quantità10) * intNum20 / 100
            risparmio10 = (intNum19 * quantità10) * intNum20 / 100
            totale10 = intNum19 * quantità10
            lbltotale10.Text = totale10.ToString("C2")
            lblrisparmio10.Text = risparmio10.ToString("C2")
            lblAnswer9.Text = intAnswer9.ToString("C2")
            txttotale10.Text = (intNum19 * quantità10).ToString("C2")
            txtintAnswer9.Text = ((intNum19 * quantità10) - (intNum19 * quantità10) * intNum20 / 100).ToString("C2")
            txtrisparmio10.Text = ((intNum19 * quantità10) * intNum20 / 100).ToString("C2")
        End If

        Dim intNum22 As Double
        Dim intNum23 As Double
        Dim intAnswer10 As Double
        Dim risparmio11 As Double
        Dim quantità11 As Integer
        Dim totale11 As Double
        Double.TryParse(txtNum22.Text, intNum22)
        Double.TryParse(txtNum23.Text, intNum23)
        Double.TryParse(txttotale11.Text, totale11)
        Double.TryParse(txtintAnswer10.Text, intAnswer10)
        Double.TryParse(txtrisparmio11.Text, risparmio11)
        Integer.TryParse(txtquantità11.Text, quantità11)

        If chkMoltiplicazione10.Checked = True Then
            intAnswer10 = (intNum22 * quantità11) - (intNum22 * quantità11) * intNum23 / 100
            risparmio11 = (intNum22 * quantità11) * intNum23 / 100
            totale11 = intNum22 * quantità11
            lbltotale11.Text = totale11.ToString("C2")
            lblrisparmio11.Text = risparmio11.ToString("C2")
            lblAnswer10.Text = intAnswer10.ToString("C2")
            txttotale11.Text = (intNum22 * quantità11).ToString("C2")
            txtintAnswer10.Text = ((intNum22 * quantità11) - (intNum22 * quantità11) * intNum23 / 100).ToString("C2")
            txtrisparmio11.Text = ((intNum22 * quantità11) * intNum23 / 100).ToString("C2")
        End If

        Dim intNum24 As Double
        Dim intNum25 As Double
        Dim intAnswer11 As Double
        Dim risparmio12 As Double
        Dim quantità12 As Integer
        Dim totale12 As Double
        Double.TryParse(txtNum24.Text, intNum24)
        Double.TryParse(txtNum25.Text, intNum25)
        Double.TryParse(txttotale12.Text, totale12)
        Double.TryParse(txtintAnswer11.Text, intAnswer11)
        Double.TryParse(txtrisparmio12.Text, risparmio12)
        Integer.TryParse(txtquantità12.Text, quantità12)

        If chkMoltiplicazione11.Checked = True Then
            intAnswer11 = (intNum24 * quantità12) - (intNum24 * quantità12) * intNum25 / 100
            risparmio12 = (intNum24 * quantità12) * intNum25 / 100
            totale12 = intNum24 * quantità12
            lbltotale12.Text = totale12.ToString("C2")
            lblrisparmio12.Text = risparmio12.ToString("C2")
            lblAnswer11.Text = intAnswer11.ToString("C2")
            txttotale12.Text = (intNum24 * quantità12).ToString("C2")
            txtintAnswer11.Text = ((intNum24 * quantità12) - (intNum24 * quantità12) * intNum25 / 100).ToString("C2")
            txtrisparmio12.Text = ((intNum24 * quantità12) * intNum25 / 100).ToString("C2")
        End If

        Dim intNum26 As Double
        Dim intNum27 As Double
        Dim intAnswer12 As Double
        Dim risparmio13 As Double
        Dim quantità13 As Integer
        Dim totale13 As Double
        Double.TryParse(txtNum26.Text, intNum26)
        Double.TryParse(txtNum27.Text, intNum27)
        Double.TryParse(txttotale13.Text, totale13)
        Double.TryParse(txtintAnswer12.Text, intAnswer12)
        Double.TryParse(txtrisparmio13.Text, risparmio13)
        Integer.TryParse(txtquantità13.Text, quantità13)

        If chkMoltiplicazione12.Checked = True Then
            intAnswer12 = (intNum26 * quantità13) - (intNum26 * quantità13) * intNum27 / 100
            risparmio13 = (intNum26 * quantità13) * intNum27 / 100
            totale13 = intNum26 * quantità13
            lbltotale13.Text = totale13.ToString("C2")
            lblrisparmio13.Text = risparmio13.ToString("C2")
            lblAnswer12.Text = intAnswer12.ToString("C2")
            txttotale13.Text = (intNum26 * quantità13).ToString("C2")
            txtintAnswer12.Text = ((intNum26 * quantità13) - (intNum26 * quantità13) * intNum27 / 100).ToString("C2")
            txtrisparmio13.Text = ((intNum26 * quantità13) * intNum27 / 100).ToString("C2")
        End If

        Dim intNum28 As Double
        Dim intNum29 As Double
        Dim intAnswer13 As Double
        Dim risparmio14 As Double
        Dim quantità14 As Integer
        Dim totale14 As Double
        Double.TryParse(txtNum28.Text, intNum28)
        Double.TryParse(txtNum29.Text, intNum29)
        Double.TryParse(txttotale14.Text, totale14)
        Double.TryParse(txtintAnswer13.Text, intAnswer13)
        Double.TryParse(txtrisparmio14.Text, risparmio14)
        Integer.TryParse(txtquantità14.Text, quantità14)

        If chkMoltiplicazione13.Checked = True Then
            intAnswer13 = (intNum28 * quantità14) - (intNum28 * quantità14) * intNum29 / 100
            risparmio14 = (intNum28 * quantità14) * intNum29 / 100
            totale14 = intNum28 * quantità14
            lbltotale14.Text = totale14.ToString("C2")
            lblrisparmio14.Text = risparmio14.ToString("C2")
            lblAnswer13.Text = intAnswer13.ToString("C2")
            txttotale14.Text = (intNum28 * quantità14).ToString("C2")
            txtintAnswer13.Text = ((intNum28 * quantità14) - (intNum28 * quantità14) * intNum29 / 100).ToString("C2")
            txtrisparmio14.Text = ((intNum28 * quantità14) * intNum29 / 100).ToString("C2")
        End If

        Dim intNum30 As Double
        Dim intNum31 As Double
        Dim intAnswer14 As Double
        Dim risparmio15 As Double
        Dim quantità15 As Integer
        Dim totale15 As Double
        Double.TryParse(txtNum30.Text, intNum30)
        Double.TryParse(txtNum31.Text, intNum31)
        Double.TryParse(txttotale15.Text, totale15)
        Double.TryParse(txtintAnswer14.Text, intAnswer14)
        Double.TryParse(txtrisparmio15.Text, risparmio15)
        Integer.TryParse(txtquantità15.Text, quantità15)

        If chkMoltiplicazione14.Checked = True Then
            intAnswer14 = (intNum30 * quantità15) - (intNum30 * quantità15) * intNum31 / 100
            risparmio15 = (intNum30 * quantità15) * intNum31 / 100
            totale15 = intNum30 * quantità15
            lbltotale15.Text = totale15.ToString("C2")
            lblrisparmio15.Text = risparmio15.ToString("C2")
            lblAnswer14.Text = intAnswer14.ToString("C2")
            txttotale15.Text = (intNum30 * quantità15).ToString("C2")
            txtintAnswer14.Text = ((intNum30 * quantità15) - (intNum30 * quantità15) * intNum31 / 100).ToString("C2")
            txtrisparmio15.Text = ((intNum30 * quantità15) * intNum31 / 100).ToString("C2")
        End If

        Dim intNum32 As Double
        Dim intNum33 As Double
        Dim intAnswer15 As Double
        Dim risparmio16 As Double
        Dim quantità16 As Integer
        Dim totale16 As Double
        Double.TryParse(txtNum32.Text, intNum32)
        Double.TryParse(txtNum33.Text, intNum33)
        Double.TryParse(txttotale16.Text, totale16)
        Double.TryParse(txtintAnswer15.Text, intAnswer15)
        Double.TryParse(txtrisparmio16.Text, risparmio16)
        Integer.TryParse(txtquantità16.Text, quantità16)

        If chkMoltiplicazione15.Checked = True Then
            intAnswer15 = (intNum32 * quantità16) - (intNum32 * quantità16) * intNum33 / 100
            risparmio16 = (intNum32 * quantità16) * intNum33 / 100
            totale16 = intNum32 * quantità16
            lbltotale16.Text = totale16.ToString("C2")
            lblrisparmio16.Text = risparmio16.ToString("C2")
            lblAnswer15.Text = intAnswer15.ToString("C2")
            txttotale16.Text = (intNum32 * quantità16).ToString("C2")
            txtintAnswer15.Text = ((intNum32 * quantità16) - (intNum32 * quantità16) * intNum33 / 100).ToString("C2")
            txtrisparmio16.Text = ((intNum32 * quantità16) * intNum33 / 100).ToString("C2")
        End If

        Dim intNum34 As Double
        Dim intNum35 As Double
        Dim intAnswer16 As Double
        Dim risparmio17 As Double
        Dim quantità17 As Integer
        Dim totale17 As Double
        Double.TryParse(txtNum34.Text, intNum34)
        Double.TryParse(txtNum35.Text, intNum35)
        Double.TryParse(txttotale17.Text, totale17)
        Double.TryParse(txtintAnswer16.Text, intAnswer16)
        Double.TryParse(txtrisparmio17.Text, risparmio17)
        Integer.TryParse(txtquantità17.Text, quantità17)

        If chkMoltiplicazione16.Checked = True Then
            intAnswer16 = (intNum34 * quantità17) - (intNum34 * quantità17) * intNum35 / 100
            risparmio17 = (intNum34 * quantità17) * intNum35 / 100
            totale17 = intNum34 * quantità17
            lbltotale17.Text = totale17.ToString("C2")
            lblrisparmio17.Text = risparmio17.ToString("C2")
            lblAnswer16.Text = intAnswer16.ToString("C2")
            txttotale17.Text = (intNum34 * quantità17).ToString("C2")
            txtintAnswer16.Text = ((intNum34 * quantità17) - (intNum34 * quantità17) * intNum35 / 100).ToString("C2")
            txtrisparmio17.Text = ((intNum34 * quantità17) * intNum35 / 100).ToString("C2")
        End If

        Dim intNum36 As Double
        Dim intNum37 As Double
        Dim intAnswer17 As Double
        Dim risparmio18 As Double
        Dim quantità18 As Integer
        Dim totale18 As Double
        Double.TryParse(txtNum36.Text, intNum36)
        Double.TryParse(txtNum37.Text, intNum37)
        Double.TryParse(txttotale18.Text, totale18)
        Double.TryParse(txtintAnswer17.Text, intAnswer17)
        Double.TryParse(txtrisparmio18.Text, risparmio18)
        Integer.TryParse(txtquantità18.Text, quantità18)

        If chkMoltiplicazione17.Checked = True Then
            intAnswer17 = (intNum36 * quantità18) - (intNum36 * quantità18) * intNum37 / 100
            risparmio18 = (intNum36 * quantità18) * intNum37 / 100
            totale18 = intNum36 * quantità18
            lbltotale18.Text = totale18.ToString("C2")
            lblrisparmio18.Text = risparmio18.ToString("C2")
            lblAnswer17.Text = intAnswer17.ToString("C2")
            txttotale18.Text = (intNum36 * quantità18).ToString("C2")
            txtintAnswer17.Text = ((intNum36 * quantità18) - (intNum36 * quantità18) * intNum37 / 100).ToString("C2")
            txtrisparmio18.Text = ((intNum36 * quantità18) * intNum37 / 100).ToString("C2")
        End If

        Dim intNum38 As Double
        Dim intNum39 As Double
        Dim intAnswer18 As Double
        Dim risparmio19 As Double
        Dim quantità19 As Integer
        Dim totale19 As Double
        Double.TryParse(txtNum38.Text, intNum38)
        Double.TryParse(txtNum39.Text, intNum39)
        Double.TryParse(txttotale19.Text, totale19)
        Double.TryParse(txtintAnswer18.Text, intAnswer18)
        Double.TryParse(txtrisparmio19.Text, risparmio19)
        Integer.TryParse(txtquantità19.Text, quantità19)

        If chkMoltiplicazione18.Checked = True Then
            intAnswer18 = (intNum38 * quantità19) - (intNum38 * quantità19) * intNum39 / 100
            risparmio19 = (intNum38 * quantità19) * intNum39 / 100
            totale19 = intNum38 * quantità19
            lbltotale19.Text = totale19.ToString("C2")
            lblrisparmio19.Text = risparmio19.ToString("C2")
            lblAnswer18.Text = intAnswer18.ToString("C2")
            txttotale19.Text = (intNum38 * quantità19).ToString("C2")
            txtintAnswer18.Text = ((intNum38 * quantità19) - (intNum38 * quantità19) * intNum39 / 100).ToString("C2")
            txtrisparmio19.Text = ((intNum38 * quantità19) * intNum39 / 100).ToString("C2")
        End If

        Dim intNum40 As Double
        Dim intNum41 As Double
        Dim intAnswer19 As Double
        Dim risparmio20 As Double
        Dim quantità20 As Integer
        Dim totale20 As Double
        Double.TryParse(txtNum40.Text, intNum40)
        Double.TryParse(txtNum41.Text, intNum41)
        Double.TryParse(txttotale20.Text, totale20)
        Double.TryParse(txtintAnswer19.Text, intAnswer19)
        Double.TryParse(txtrisparmio20.Text, risparmio20)
        Integer.TryParse(txtquantità20.Text, quantità20)

        If chkMoltiplicazione19.Checked = True Then
            intAnswer19 = (intNum40 * quantità20) - (intNum40 * quantità20) * intNum41 / 100
            risparmio20 = (intNum40 * quantità20) * intNum41 / 100
            totale20 = intNum40 * quantità20
            lbltotale20.Text = totale20.ToString("C2")
            lblrisparmio20.Text = risparmio20.ToString("C2")
            lblAnswer19.Text = intAnswer19.ToString("C2")
            txttotale20.Text = (intNum40 * quantità20).ToString("C2")
            txtintAnswer19.Text = ((intNum40 * quantità20) - (intNum40 * quantità20) * intNum41 / 100).ToString("C2")
            txtrisparmio20.Text = ((intNum40 * quantità20) * intNum41 / 100).ToString("C2")
        End If

        Dim intNum42 As Double
        Dim intNum43 As Double
        Dim intAnswer20 As Double
        Dim risparmio21 As Double
        Dim quantità21 As Integer
        Dim totale21 As Double
        Double.TryParse(txtNum42.Text, intNum42)
        Double.TryParse(txtNum43.Text, intNum43)
        Double.TryParse(txttotale21.Text, totale21)
        Double.TryParse(txtintAnswer20.Text, intAnswer20)
        Double.TryParse(txtrisparmio21.Text, risparmio21)
        Integer.TryParse(txtquantità21.Text, quantità21)

        If chkMoltiplicazione20.Checked = True Then
            intAnswer20 = (intNum42 * quantità21) - (intNum42 * quantità21) * intNum43 / 100
            risparmio21 = (intNum42 * quantità21) * intNum43 / 100
            totale21 = intNum42 * quantità21
            lbltotale21.Text = totale21.ToString("C2")
            lblrisparmio21.Text = risparmio21.ToString("C2")
            lblAnswer20.Text = intAnswer20.ToString("C2")
            txttotale21.Text = (intNum42 * quantità21).ToString("C2")
            txtintAnswer20.Text = ((intNum42 * quantità21) - (intNum42 * quantità21) * intNum43 / 100).ToString("C2")
            txtrisparmio21.Text = ((intNum42 * quantità21) * intNum43 / 100).ToString("C2")
        End If

        Dim intNum44 As Double
        Dim intNum45 As Double
        Dim intAnswer21 As Double
        Dim risparmio22 As Double
        Dim quantità22 As Integer
        Dim totale22 As Double
        Double.TryParse(txtNum44.Text, intNum44)
        Double.TryParse(txtNum45.Text, intNum45)
        Double.TryParse(txttotale22.Text, totale22)
        Double.TryParse(txtintAnswer21.Text, intAnswer21)
        Double.TryParse(txtrisparmio22.Text, risparmio22)
        Integer.TryParse(txtquantità22.Text, quantità22)

        If chkMoltiplicazione21.Checked = True Then
            intAnswer21 = (intNum44 * quantità22) - (intNum44 * quantità22) * intNum45 / 100
            risparmio22 = (intNum44 * quantità22) * intNum45 / 100
            totale22 = intNum44 * quantità22
            lbltotale22.Text = totale22.ToString("C2")
            lblrisparmio22.Text = risparmio22.ToString("C2")
            lblAnswer21.Text = intAnswer21.ToString("C2")
            txttotale22.Text = (intNum44 * quantità22).ToString("C2")
            txtintAnswer21.Text = ((intNum44 * quantità22) - (intNum44 * quantità22) * intNum45 / 100).ToString("C2")
            txtrisparmio22.Text = ((intNum44 * quantità22) * intNum45 / 100).ToString("C2")
        End If

        Dim intNum46 As Double
        Dim intNum47 As Double
        Dim intAnswer22 As Double
        Dim risparmio23 As Double
        Dim quantità23 As Integer
        Dim totale23 As Double
        Double.TryParse(txtNum46.Text, intNum46)
        Double.TryParse(txtNum47.Text, intNum47)
        Double.TryParse(txttotale23.Text, totale23)
        Double.TryParse(txtintAnswer22.Text, intAnswer22)
        Double.TryParse(txtrisparmio23.Text, risparmio23)
        Integer.TryParse(txtquantità23.Text, quantità23)

        If chkMoltiplicazione22.Checked = True Then
            intAnswer22 = (intNum46 * quantità23) - (intNum46 * quantità23) * intNum47 / 100
            risparmio23 = (intNum46 * quantità23) * intNum47 / 100
            totale23 = intNum46 * quantità23
            lbltotale23.Text = totale23.ToString("C2")
            lblrisparmio23.Text = risparmio23.ToString("C2")
            lblAnswer22.Text = intAnswer22.ToString("C2")
            txttotale23.Text = (intNum46 * quantità23).ToString("C2")
            txtintAnswer22.Text = ((intNum46 * quantità23) - (intNum46 * quantità23) * intNum47 / 100).ToString("C2")
            txtrisparmio23.Text = ((intNum46 * quantità23) * intNum47 / 100).ToString("C2")
        End If

        Dim intNum48 As Double
        Dim intNum49 As Double
        Dim intAnswer23 As Double
        Dim risparmio24 As Double
        Dim quantità24 As Integer
        Dim totale24 As Double
        Double.TryParse(txtNum48.Text, intNum48)
        Double.TryParse(txtNum49.Text, intNum49)
        Double.TryParse(txttotale24.Text, totale24)
        Double.TryParse(txtintAnswer23.Text, intAnswer23)
        Double.TryParse(txtrisparmio24.Text, risparmio24)
        Integer.TryParse(txtquantità24.Text, quantità24)

        If chkMoltiplicazione23.Checked = True Then
            intAnswer23 = (intNum48 * quantità24) - (intNum48 * quantità24) * intNum49 / 100
            risparmio24 = (intNum48 * quantità24) * intNum49 / 100
            totale24 = intNum48 * quantità24
            lbltotale24.Text = totale24.ToString("C2")
            lblrisparmio24.Text = risparmio24.ToString("C2")
            lblAnswer23.Text = intAnswer23.ToString("C2")
            txttotale24.Text = (intNum48 * quantità24).ToString("C2")
            txtintAnswer23.Text = ((intNum48 * quantità24) - (intNum48 * quantità24) * intNum49 / 100).ToString("C2")
            txtrisparmio24.Text = ((intNum48 * quantità24) * intNum49 / 100).ToString("C2")
        End If

        Dim intNum50 As Double
        Dim intNum51 As Double
        Dim intAnswer24 As Double
        Dim risparmio25 As Double
        Dim quantità25 As Integer
        Dim totale25 As Double
        Double.TryParse(txtNum50.Text, intNum50)
        Double.TryParse(txtNum51.Text, intNum51)
        Double.TryParse(txttotale25.Text, totale25)
        Double.TryParse(txtintAnswer24.Text, intAnswer24)
        Double.TryParse(txtrisparmio25.Text, risparmio25)
        Integer.TryParse(txtquantità25.Text, quantità25)

        If chkMoltiplicazione24.Checked = True Then
            intAnswer24 = (intNum50 * quantità25) - (intNum50 * quantità25) * intNum51 / 100
            risparmio25 = (intNum50 * quantità25) * intNum51 / 100
            totale25 = intNum50 * quantità25
            lbltotale25.Text = totale25.ToString("C2")
            lblrisparmio25.Text = risparmio25.ToString("C2")
            lblAnswer24.Text = intAnswer24.ToString("C2")
            txttotale25.Text = (intNum50 * quantità25).ToString("C2")
            txtintAnswer24.Text = ((intNum50 * quantità25) - (intNum50 * quantità25) * intNum51 / 100).ToString("C2")
            txtrisparmio25.Text = ((intNum50 * quantità25) * intNum51 / 100).ToString("C2")
            txttotalecomplessivo.Text = (totale1 + totale2 + totale3 + totale4 + totale5 + totale6 + totale7 + totale8 + totale9 + totale10 + totale11 + totale12 + totale13 + totale14 + totale15 + totale16 + totale17 + totale18 + totale20 + totale21 + totale22 + totale23 + totale24 + totale25).ToString("C2")
            txttotalesconto.Text = (intAnswer + intAnswer1 + intAnswer2 + intAnswer3 + intAnswer4 + intAnswer5 + intAnswer6 + intAnswer7 + intAnswer8 + intAnswer9 + intAnswer10 + intAnswer11 + intAnswer12 + intAnswer13 + intAnswer14 + intAnswer15 + intAnswer16 + intAnswer17 + intAnswer18 + intAnswer19 + intAnswer20 + intAnswer21 + intAnswer22 + intAnswer23 + intAnswer24).ToString("C2")
            txttotalerisparmio.Text = (risparmio1 + risparmio2 + risparmio3 + risparmio4 + risparmio5 + risparmio6 + risparmio7 + risparmio8 + risparmio9 + risparmio10 + risparmio10 + risparmio11 + risparmio12 + risparmio13 + risparmio14 + risparmio15 + risparmio16 + risparmio17 + risparmio18 + risparmio19 + risparmio20 + risparmio21 + risparmio22 + risparmio23 + risparmio24 + risparmio25).ToString("C2")
        End If
    End Sub

    Private Sub btncancella_Click(sender As Object, e As EventArgs) Handles btncancella.Click
        txtNum1.Clear()
        txtNum2.Clear()
        txtNum3.Clear()
        txtNum4.Clear()
        txtNum5.Clear()
        txtNum6.Clear()
        txtNum7.Clear()
        txtNum8.Clear()
        txtNum9.Clear()
        txtNum10.Clear()
        txtNum11.Clear()
        txtNum12.Clear()
        txtNum13.Clear()
        txtNum14.Clear()
        txtNum15.Clear()
        txtNum16.Clear()
        txtNum17.Clear()
        txtNum18.Clear()
        txtNum19.Clear()
        txtNum20.Clear()
        txtNum22.Clear()
        txtNum23.Clear()
        txtNum24.Clear()
        txtNum25.Clear()
        txtNum26.Clear()
        txtNum27.Clear()
        txtNum28.Clear()
        txtNum29.Clear()
        txtNum30.Clear()
        txtNum31.Clear()
        txtNum32.Clear()
        txtNum33.Clear()
        txtNum34.Clear()
        txtNum35.Clear()
        txtNum36.Clear()
        txtNum37.Clear()
        txtNum38.Clear()
        txtNum39.Clear()
        txtNum40.Clear()
        txtNum41.Clear()
        txtNum42.Clear()
        txtNum43.Clear()
        txtNum44.Clear()
        txtNum45.Clear()
        txtNum46.Clear()
        txtNum47.Clear()
        txtNum48.Clear()
        txtNum49.Clear()
        txtNum50.Clear()
        txtNum51.Clear()
        txtquantità1.Clear()
        txtquantità2.Clear()
        txtquantità3.Clear()
        txtquantità4.Clear()
        txtquantità5.Clear()
        txtquantità6.Clear()
        txtquantità7.Clear()
        txtquantità8.Clear()
        txtquantità9.Clear()
        txtquantità10.Clear()
        txtquantità11.Clear()
        txtquantità12.Clear()
        txtquantità13.Clear()
        txtquantità14.Clear()
        txtquantità15.Clear()
        txtquantità16.Clear()
        txtquantità17.Clear()
        txtquantità18.Clear()
        txtquantità19.Clear()
        txtquantità20.Clear()
        txtquantità21.Clear()
        txtquantità22.Clear()
        txtquantità24.Clear()
        txtquantità25.Clear()
        chkMoltiplicazione.Checked = False
        chkMoltiplicazione1.Checked = False
        chkMoltiplicazione2.Checked = False
        chkMoltiplicazione3.Checked = False
        chkMoltiplicazione4.Checked = False
        chkMoltiplicazione5.Checked = False
        chkMoltiplicazione6.Checked = False
        chkMoltiplicazione7.Checked = False
        chkMoltiplicazione8.Checked = False
        chkMoltiplicazione9.Checked = False
        chkMoltiplicazione10.Checked = False
        chkMoltiplicazione11.Checked = False
        chkMoltiplicazione12.Checked = False
        chkMoltiplicazione13.Checked = False
        chkMoltiplicazione14.Checked = False
        chkMoltiplicazione15.Checked = False
        chkMoltiplicazione16.Checked = False
        chkMoltiplicazione17.Checked = False
        chkMoltiplicazione18.Checked = False
        chkMoltiplicazione19.Checked = False
        chkMoltiplicazione20.Checked = False
        chkMoltiplicazione21.Checked = False
        chkMoltiplicazione22.Checked = False
        chkMoltiplicazione23.Checked = False
        chkMoltiplicazione24.Checked = False
        lbltotale1.Text = String.Empty
        lbltotale2.Text = String.Empty
        lbltotale3.Text = String.Empty
        lbltotale4.Text = String.Empty
        lbltotale5.Text = String.Empty
        lbltotale6.Text = String.Empty
        lbltotale7.Text = String.Empty
        lbltotale8.Text = String.Empty
        lbltotale9.Text = String.Empty
        lbltotale10.Text = String.Empty
        lbltotale11.Text = String.Empty
        lbltotale12.Text = String.Empty
        lbltotale13.Text = String.Empty
        lbltotale14.Text = String.Empty
        lbltotale15.Text = String.Empty
        lbltotale16.Text = String.Empty
        lbltotale17.Text = String.Empty
        lbltotale18.Text = String.Empty
        lbltotale19.Text = String.Empty
        lbltotale20.Text = String.Empty
        lbltotale21.Text = String.Empty
        lbltotale22.Text = String.Empty
        lbltotale23.Text = String.Empty
        lbltotale24.Text = String.Empty
        lbltotale25.Text = String.Empty
        lblAnswer.Text = String.Empty
        lblAnswer1.Text = String.Empty
        lblAnswer2.Text = String.Empty
        lblAnswer3.Text = String.Empty
        lblAnswer4.Text = String.Empty
        lblAnswer5.Text = String.Empty
        lblAnswer6.Text = String.Empty
        lblAnswer7.Text = String.Empty
        lblAnswer8.Text = String.Empty
        lblAnswer9.Text = String.Empty
        lblAnswer10.Text = String.Empty
        lblAnswer11.Text = String.Empty
        lblAnswer12.Text = String.Empty
        lblAnswer13.Text = String.Empty
        lblAnswer14.Text = String.Empty
        lblAnswer15.Text = String.Empty
        lblAnswer16.Text = String.Empty
        lblAnswer17.Text = String.Empty
        lblAnswer18.Text = String.Empty
        lblAnswer19.Text = String.Empty
        lblAnswer20.Text = String.Empty
        lblAnswer21.Text = String.Empty
        lblAnswer22.Text = String.Empty
        lblAnswer23.Text = String.Empty
        lblAnswer24.Text = String.Empty
        lblrisparmio1.Text = String.Empty
        lblrisparmio2.Text = String.Empty
        lblrisparmio3.Text = String.Empty
        lblrisparmio4.Text = String.Empty
        lblrisparmio5.Text = String.Empty
        lblrisparmio6.Text = String.Empty
        lblrisparmio7.Text = String.Empty
        lblrisparmio8.Text = String.Empty
        lblrisparmio9.Text = String.Empty
        lblrisparmio10.Text = String.Empty
        lblrisparmio11.Text = String.Empty
        lblrisparmio12.Text = String.Empty
        lblrisparmio13.Text = String.Empty
        lblrisparmio14.Text = String.Empty
        lblrisparmio15.Text = String.Empty
        lblrisparmio16.Text = String.Empty
        lblrisparmio17.Text = String.Empty
        lblrisparmio18.Text = String.Empty
        lblrisparmio19.Text = String.Empty
        lblrisparmio20.Text = String.Empty
        lblrisparmio21.Text = String.Empty
        lblrisparmio22.Text = String.Empty
        lblrisparmio23.Text = String.Empty
        lblrisparmio24.Text = String.Empty
        lblrisparmio25.Text = String.Empty
        txttotale1.Clear()
        txttotale2.Clear()
        txttotale3.Clear()
        txttotale4.Clear()
        txttotale5.Clear()
        txttotale6.Clear()
        txttotale7.Clear()
        txttotale8.Clear()
        txttotale9.Clear()
        txttotale10.Clear()
        txttotale11.Clear()
        txttotale12.Clear()
        txttotale13.Clear()
        txttotale14.Clear()
        txttotale15.Clear()
        txttotale16.Clear()
        txttotale17.Clear()
        txttotale18.Clear()
        txttotale19.Clear()
        txttotale20.Clear()
        txttotale21.Clear()
        txttotale22.Clear()
        txttotale23.Clear()
        txttotale24.Clear()
        txttotale25.Clear()
        txttotalecomplessivo.Clear()
        txtintAnswer.Clear()
        txtintAnswer1.Clear()
        txtintAnswer2.Clear()
        txtintAnswer3.Clear()
        txtintAnswer4.Clear()
        txtintAnswer5.Clear()
        txtintAnswer6.Clear()
        txtintAnswer7.Clear()
        txtintAnswer8.Clear()
        txtintAnswer9.Clear()
        txtintAnswer10.Clear()
        txtintAnswer11.Clear()
        txtintAnswer12.Clear()
        txtintAnswer13.Clear()
        txtintAnswer14.Clear()
        txtintAnswer15.Clear()
        txtintAnswer16.Clear()
        txtintAnswer17.Clear()
        txtintAnswer18.Clear()
        txtintAnswer19.Clear()
        txtintAnswer20.Clear()
        txtintAnswer21.Clear()
        txtintAnswer22.Clear()
        txtintAnswer23.Clear()
        txtintAnswer24.Clear()
        txttotalesconto.Clear()
        txtrisparmio1.Clear()
        txtrisparmio2.Clear()
        txtrisparmio3.Clear()
        txtrisparmio4.Clear()
        txtrisparmio5.Clear()
        txtrisparmio6.Clear()
        txtrisparmio7.Clear()
        txtrisparmio8.Clear()
        txtrisparmio9.Clear()
        txtrisparmio10.Clear()
        txtrisparmio11.Clear()
        txtrisparmio12.Clear()
        txtrisparmio13.Clear()
        txtrisparmio14.Clear()
        txtrisparmio15.Clear()
        txtrisparmio16.Clear()
        txtrisparmio17.Clear()
        txtrisparmio18.Clear()
        txtrisparmio19.Clear()
        txtrisparmio20.Clear()
        txtrisparmio21.Clear()
        txtrisparmio22.Clear()
        txtrisparmio23.Clear()
        txtrisparmio24.Clear()
        txtrisparmio25.Clear()
        txttotalerisparmio.Clear()
        txtNum1.Focus()
    End Sub

    Private Sub Button1_Click(sender As Object, e As EventArgs) Handles Button1.Click
        Me.Close()
    End Sub

    Private Sub btnstampa_Click(sender As Object, e As EventArgs) Handles btnstampa.Click
        PrintForm1.PrintAction = Printing.PrintAction.PrintToPreview
        PrintForm1.Print()
    End Sub
End Class
