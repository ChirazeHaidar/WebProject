# WebProject

Ce premier commit est juste pour mettre la structure du projet web et standardiser la manière dont on va créer les packages et répertoires ainsi que la convention des noms des classes, packages,....</br>
        Pour chaque module on va creer des packages ayant le nom du module sous les packages principaux où on va créer nos fichiers JAVA:
             -cnam.gestionstock.bean
             -cnam.gestionstock.dao
             -cnam.gestionstock.servlet
   
    Par exemple pour le module item on aura les packages suivants:
   
        cnam.gestionstock.bean.item
        cnam.gestionstock.dao.item
        cnam.gestionstock.servlet.item
  
    N.B: Tous les lettres du nom d'un package doivent être minuscule.
    
	
    De même pour la partie interface, pour chaque module on va créer un répertoire ayant le même nom du module (toutes les lettres étant en minuscule) sous la répertoire 'jsp'.
    Les noms des classes et interfaces JAVA doivent toujours commencer par des lettres majuscules et doivent toujours contenir les préfixes suivant par analogie avec
    leur packages:'Servlet','Bean','DAO','DAOImpl'.
    Les noms des fichiers JSP doivent toujours commencer par des lettres minuscules.
    Le flux des requests va être le suivant:
    JSP-->Servlet-->(DAO;DAOImpl)-->BD-->(DAO;DAOImpl)-->Servlet-->JSP
