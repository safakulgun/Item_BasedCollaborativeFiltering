# Item_BasedCollaborativeFiltering
Online bir film izleme platformu iş birlikçi filtreleme yöntemi ile bir öneri sistemi geliştirmek istemektedir.
İçerik temelli öneri sistemlerini deneyen şirket topluluğun kanaatlerini barındıracak şekilde öneriler geliştirmek istemektedir.
Kullanıcılar bir filmi beğendiğindde o film ile benzer beğenilme örüntüsüne sahip olan diğer filmler önerilmek istenmektedir.
VERİ SETİ HİKAYESİ
Veri seti MovieLens tarafından sağlanmıştır.
İçerisinde filmler ve bu filmlere verilen puanları barınddırmaktadır.
Veri seti yaklaşık 27000 film için 2000000 derecelendirme içermektedir.
DEĞİŞKENLER
movie.csv
movieID: Eşsiz film numarası (UniqueID)
title : Film Adı
rating.csv
userID: Eşsiz kullanıcı numarası (UniqueID)
movieID :Eşsiz film numarası
rating:Kullanıcı tarafından verilen puan 
timestamp: Değerlendirme  tarihi
