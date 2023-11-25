<![endif]-->

# מרפאה

## לקוחות

 - ת.ז.
 - שם
 - ת. לידה
 - כתובת
 - פרטי אמצעי תשלום
 - טלפון
 - הערות

## רופאים

 - ת.ז.
 - קוד רופא
 - שם
 - ת. לידה
 - כתובת
 - התמחות ENUM
 - טלפון
 - משמרות

## תורים (מקשר)

 - קוד תור
 - קוד רופא
 - קוד לקוח
 - שעה
 - תאריך
 - חדר
 - סוג טיפול ENUM
 - מחיר
 - משך זמן טיפול

## תיאור

מערכת בסיסית לניהול תורים במרפאה – קביעת תור, לקוח חדש, רופא חדש, שמירת פרטי לקוחות ורופאים. המערכת מכילה טבלאות של רופאים, מטופלים, תורים ועוד.

## מיפוי

**מטופלים** 

> שליפת רשימת מטופלים
> 
> GET [https://clinic/clients](https://mirpaha.co.il/clients)
> 
> שליפת מטופל ע"פ מזהה
> 
> GET [https://clinic/clients/id](https://mirpaha.co.il/clients/id)
> 
> הוספת מטופל
> 
> POST [https://clinic/clients](https://mirpaha.co.il/clients)
> 
> עדכון מטופל
> 
> PUT [https://clinic/clients/id](https://mirpaha.co.il/clients/id)
> 
> הוספת הערות למטופל
> 
> PUT
> [https://clinic/clients/id/comments](https://mirpaha.co.il/clients/id/comments)
> 
> מחיקת מטופל
> 
> DELETE [https://clinic/clients/id](https://mirpaha.co.il/clients/id)

**רופאים** 

> שליפת רשימת רופאים
> 
> GET [https://clinic/doctors](https://mirpaha.co.il/doctors)
> 
> שליפת רופא ע"פ מזהה
> 
> GET [https://clinic/doctors/code](https://mirpaha.co.il/doctors/code)
> 
> שליפת רשימת התמחויות לרופא
> 
> GET
> [https://clinic/doctors/code/specialization](https://mirpaha.co.il/doctors/code/specialization)
> 
> הוספת רופא
> 
> POST [https://clinic/doctors](https://mirpaha.co.il/doctors)
> 
> עדכון רופא
> 
> PUT [https://clinic/doctors/code](https://mirpaha.co.il/doctors/code)
> 
> מחיקת רופא
> 
> DELETE
> [https://clinic/doctors/code](https://mirpaha.co.il/doctors/code)

**תורים** 

> שליפת רשימת תורים
> 
> GET [https://clinic/appointment](https://mirpaha.co.il/appointment)
> 
> שליפת רשימת תורים של מטופל
> 
> GET
> [https://clinic/appointment/clients/clientid](https://mirpaha.co.il/appointment/clientid)
> 
> שליפת תור ע"פ מזהה
> 
> GET
> [https://clinic/appointment/id](https://mirpaha.co.il/appointment/id)
> 
> הוספת תור
> 
> POST [https://clinic/appointment](https://mirpaha.co.il/appointment)
> 
> עדכון תור
> 
> PUT
> [https://clinic/appointment/id](https://mirpaha.co.il/appointment/id)
> 
> מחיקת תור
> 
> DELETE
> [https://clinic/appointment/id](https://mirpaha.co.il/appointment/id)
