This is the implimentation of yolov3 paper in tensorflow 2.2 framework



[Yolov3 paper](https://pjreddie.com/media/files/papers/YOLOv3.pdf)


Layer visulization

![modellayers](https://www.kaggleusercontent.com/kf/38681559/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..F7Zc6xrNF_K8Nuw8-22QYQ.e9tDp7q6R_hMeNu4eSr6y451GBPRSN6ZcR-OUPC8taSUSFHHVll871Uarc_Bz-UzZw7xWLNcJvz6uXDpWFbZ5Z4TbV5tTCGP3AASL41-G1SpFUNEJmfZl3EEhDLOQx6U6BIUgMFu3fH7IA-eG_YKd84bzUcrqJ_2R-JhxnJUONuM-cDvGRMKsdCf_Q53D062nAJVxxBoB5zu4tN22DARsOct8FypgYV2-afWrkZg4IBu6EBnV8QQRsa-zsxTvZkfvWpL2hJzsDSljsCiL54mUHJVet5CPsox26TJhERDwGfW9U2h_BsRNNKplnL8e9ap-ilpVSShEH3Fzj6IdoX7mGWEY5-RjbPlrsE5f8WLOblZNqbd1O15VmeC8zBOOEBT9LqJJzwZz3lO5lWC5Hskf9u35Lg_6NRaYm0k9MgEotmXCvqZb_JSdVQKeSyqUok9P7tt37vwtkchBa6tduur3gTRxHe-TVGAM7-Uqo3OcBWdLGjqfe0af12lwq9EXbNpZj8dvcUAbgKCc_AjRhHDT711LNxpxB-vFGF06lr3Qmph0xqNJ2Lu7xqWhVffX0q7r0Amjgwr_LQl_3EDsCzNSjcj8WpaOK35pbieuQypnvHhpEO5NNDO4cyvjNiLBih_CDyX1Uyam9enEbU4MjGcoP39Hmy410_pViU7dvVe8GFtFIJMMxqX6ZNzH2GJihje.QaraFMHNUgY2cTkWfj2fnw/__results___files/__results___65_0.png)






some test images
![visulize](https://www.kaggleusercontent.com/kf/38681559/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..F7Zc6xrNF_K8Nuw8-22QYQ.e9tDp7q6R_hMeNu4eSr6y451GBPRSN6ZcR-OUPC8taSUSFHHVll871Uarc_Bz-UzZw7xWLNcJvz6uXDpWFbZ5Z4TbV5tTCGP3AASL41-G1SpFUNEJmfZl3EEhDLOQx6U6BIUgMFu3fH7IA-eG_YKd84bzUcrqJ_2R-JhxnJUONuM-cDvGRMKsdCf_Q53D062nAJVxxBoB5zu4tN22DARsOct8FypgYV2-afWrkZg4IBu6EBnV8QQRsa-zsxTvZkfvWpL2hJzsDSljsCiL54mUHJVet5CPsox26TJhERDwGfW9U2h_BsRNNKplnL8e9ap-ilpVSShEH3Fzj6IdoX7mGWEY5-RjbPlrsE5f8WLOblZNqbd1O15VmeC8zBOOEBT9LqJJzwZz3lO5lWC5Hskf9u35Lg_6NRaYm0k9MgEotmXCvqZb_JSdVQKeSyqUok9P7tt37vwtkchBa6tduur3gTRxHe-TVGAM7-Uqo3OcBWdLGjqfe0af12lwq9EXbNpZj8dvcUAbgKCc_AjRhHDT711LNxpxB-vFGF06lr3Qmph0xqNJ2Lu7xqWhVffX0q7r0Amjgwr_LQl_3EDsCzNSjcj8WpaOK35pbieuQypnvHhpEO5NNDO4cyvjNiLBih_CDyX1Uyam9enEbU4MjGcoP39Hmy410_pViU7dvVe8GFtFIJMMxqX6ZNzH2GJihje.QaraFMHNUgY2cTkWfj2fnw/__results___files/__results___56_0.png)
