Module Module1

    Sub Main()
        Dim joursLocation1, t_diesel, t_essence, t_km_essence, t_km_diesel, nb_j, dis, t_total_diesel, t_total_essence, dis_total_essence, dis_total_diesel As Double

        Console.WriteLine("nombre de jours de locatrion")
        nb_j = Console.ReadLine()
        Console.WriteLine("nombre de km à parcourir")
        dis = Console.ReadLine()
        t_total_essence = 30 * nb_j
        dis_total_essence = 0.85 * dis
        t_total_diesel = 35 * dis
        dis_total_diesel = 0.65 * dis
        Console.WriteLine("le montant du au km (essence) est : " + dis_total_essence.ToString())
    End Sub
End Module
