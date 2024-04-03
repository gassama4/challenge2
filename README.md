<?php
    $message1 = "0@sn9sirppa@#?ia'jgtvryko1";
    $message2 = "q8e?wsellecif@#?sel@#?setuotpazdsy0*b9+mw@x1vj";
    $message3 = "aopi?sgnirts@#?sedhtg+p9l!";
    

    $longueur1 = strlen($message1);
    $cle1 = floor($longueur1 / 2);
    $sousChaine1 = substr($message1, 5, $cle1);
    $sousChaine1 = str_replace('@#?', ' ', $sousChaine1);
    $messageFinal1 = strrev($sousChaine1);
    echo $messageFinal1;
    echo ' ';

    $longueur2 = strlen($message2);
    $cle2 = floor($longueur2 / 2);
    $sousChaine2 = substr($message2, 5, $cle2);
    $sousChaine2 = str_replace('@#?', ' ', $sousChaine2);
    $messageFinal2 = strrev($sousChaine2);
    echo $messageFinal2;
    echo ' ';
     
    $longueur3 = strlen($message3);
    $cle3 = floor($longueur3 / 2);
    $sousChaine3 = substr($message3, 5, $message3);
    $sousChaine3 = str_replace('@#?', ' ', $sousChaine3);
    $messageFinal3 = strrev($sousChaine3);
    echo $messageFinal3;
    

   
    
?>
