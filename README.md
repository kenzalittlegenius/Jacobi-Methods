# Jacobi-Methods
Pour compiler le programme 
> ./compilegcc TP2-IFT2425 

Pour executer par exemple
> TP2-IFT2425 rubikseq0.pgm rubikseq1.pgm 500

 //------------------------------------------------------------
 // Estimation du Flux Optique de Horn & Schunk [par Jacobi]
 //
 // L'image 1 et 2 sont enregistrée dans les tableau 2D Img1[][] et Img2[][]
 // Ix, Iy, It sont des tableaux 2D de même dimension que l'image qui ont été allouées
 // VxM, VyM  Vecteur Vx & Vy moyenné aussi
 // OptFl_Vx, OptFl_Vy qui contiendra le flot optique 
 //
 //-----------------------------------------------------------