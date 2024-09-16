Module Module1

    Sub Main()
        Dim joursLocation1 As Integer = 10
        Dim distance1 As Integer = 1000
        Dim joursLocation2 As Integer = 2
        Dim distance2 As Integer = 30
        ' Déterminer le meilleur choix pour le premier scénario
        Dim choixCarburant1 As String = ChoixCarburant(joursLocation1, distance1)
        Console.WriteLine("Pour " & joursLocation1 & " jours de location et " & distance1 & " km à parcourir, le meilleur choix est : " & choixCarburant1)
        ' Déterminer le meilleur choix pour le deuxième scénario
        Dim choixCarburant2 As String = ChoixCarburant(joursLocation2, distance2)
        Console.WriteLine("Pour " & joursLocation2 & " jours de location et " & distance2 & " km à parcourir, le meilleur choix est : " & choixCarburant2)
        ' Attendre que l'utilisateur appuie sur une touche avant de fermer la console
        Console.WriteLine("Appuyez sur une touche pour quitter...")
        Console.ReadKey()

    End Sub

End Module
