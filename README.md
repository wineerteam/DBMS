

# DBMS

ER modal bana ne ke baad redundency aa gya --==>>
redundency ko kam karne ke liye normalization aaya >>>>>>
Normalization aaya to split file jada ho gya jise retriving me problem >>>>>>
retriving ko fast karne ke liye Indexing aa gya--==>>
Indexing ke karan space jada lagta hai but retriving very fast--==>>
but data ko sorting hona chahiye tabhi binary search lag skta hai 
sorting ke aane se file ke inserting or deleting me problem ho gya --==>>
but Indexingn se fast retriving hota hai --==>>
ek hi file me multiple tarike se indexing kiya ja skta hai --==>>
basisi of primary key ,name or other attrubuts --==>>
INDEXING KA KAM HAI RETRIVING OF DATA IN DATA BASE SE FAST KARNA (log2() ) time lagta hai .--==>>
main file sorted or usorted ho skte hai but INDEXING FILE HAMESA SORTED HI HONGE NHI TO FIR INDEX KA KYA KAM HOGA--==>>--==>>
--==>>

INDEXING KA ADVANTAGE HAI TIME AND DISADVAANTAGE HAI SPCAE AND MONEY 

INDEX FILE KE ANDAR DO HI COLUMN THE FIRST PRIMARY KEY AND DUSRA PINTER 
jitne main file me block honge utne hi index file me rows honge 


--=--==>>--==>>--==>>--==>>--==>>--==>>=>>
#################         @@@@   CLUSTERED INDEXING: --==>>jo indexing sorted to hai but key nhi hai usse culustered indexing bolte hai 
--->> No of entries in the index file == no of values of the attributes on which  indexing is done
sare unique vlaue of entre deni hogi so data base kharch bahut jada hoga but possible hai 
--==>> jinte main file me utni hi index file me entre hogi 
Ye sparse and dense dono hai


...................................
TYPES OF INDEXING 
1.primary indexing 
2.Secondry indexing 
dono ka kam ka hai but primary me sorted file ke liye hai 
but secondry unsorted file ke liye hai 
but dono jaruri hai

DENSE : --- agar main file me jitne bhi hai sab ko agar entre file indexin me to dense hai 
Sparse: ---- agar sab ko entre n mile count me to us use sparse kahte hai


BINARY TREEE ::: 000
 tin value ek line me order wise aayenge or jo mid wala hai wo uper pushh ho jayega 
 esi trahs se left and right me shift hote hote ek tree ban jata hai 

 ######@@@@@@@@@@@@@###########
 1. ER MDOEL BANAYE
 2. RELATION DATA
 3. NORMALIZATION
 4. INDEXING
 5. YE SAB KAM KYO KIEY FOR THE INDEDXING

 6. AB MAIN KAM FOR THE EXAM AND PLACMENT PURPOSE
 7. QUERY LANGUAGE SIKHNA HAI @@@@@@@@@@@@@################## FOR RETRIVE THE DATA
 8. TWO TYPES
 9. 1. procedural
    2. 2. Non-Procedural

       1. Relational Algebara is Precedural
       2. 2. Relational Calculus is Non-procedural
          3. dono use kar ke SQL bana te hai
             YE DONO KA IDEA USE KARTA HAI
             jis me jada weighteage hota hai algebra
          
 10. Procedural : -- kaha chahiye or kya chahiye wo mention karte hai
 11. Non-procedural : --ye mention kare kya chahiey but ye n bataye ki kasie chahiye :
     ye bhi two parr me hai : tuple relation calculas , Domain relation Calculas
     i.
RELATION ALGEBRA: mathemetical operators:
table me oprands hai
*( table ) -->>
input single table and doubletable input ho skta hai
No dublication ,
   select --- sigma
   project----phi
   union-----U
  set difference--- ( - )
 corss product :  X
 Rename:       (row in math symbol)
2:55 LECTURE 

