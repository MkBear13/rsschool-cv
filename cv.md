# CV
## 1)Mikhail Kovalev
## 2)Gmail: manutdsinse1878@gmail.com
## 3)Try to learn something new. Good at refactoring of otyhers code.
## 4)Skills: C#, ASP.NET, Python(little bit), HTML, CSS
## 5) [Who likes it?](https://www.codewars.com/kata/5266876b8f4bf2da9b000362)
      using System;
      public static class Kata
      {
        public static string Likes(string[] name)
        {
          if(name.Length==0) return "no one likes this";
          else if (name.Length == 1) return string.Format("{0} likes this", name[0]) ;
          else if (name.Length==2) return string.Format("{0} and {1} like this", name[0],name[1]) ;
          else if (name.Length==3) return string.Format("{0}, {1} and {2} like this", name[0],name[1],name[2]);
          else  return string.Format("{0}, {1} and {2} others like this", name[0],name[1], name.Length-2);
        }
      }
      
## [Regex validate PIN code](https://www.codewars.com/kata/55f8a9c06c018a0d6e000132)
      using System;
      using System.Text.RegularExpressions;
      public class Kata
      {
        public static bool ValidatePin(string pin)
        {
          return Regex.IsMatch(pin, @"\n", RegexOptions.Multiline)? false : Regex.IsMatch(pin,@"^[0-9]{4}$")? true:Regex.IsMatch(pin,@"^[0-9]{6}$")? true : false;
        }
      }
## 6) Work's now with 1C
## 7) Belarusian-Russian University: engineer - programmer
## 8) B1
