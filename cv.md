# CV (Curriculum Vitae)
***

## 1. Name and surname
**Dmitry Tsarykau**
***

## 2. Contacts
- **Phone**: +375291941134
- **E-mail**: dimacarikov@gmail.com
***

## 3. A brief information about myself
I am an experienced developer with an unique combination of skills and a passion for building quality software. My work experience includes developing web applications using modern technology. I strive to continually learn and improve my skills.
***

## 4. Skills
- **Programming languages**:JavaScript, C#
- **Version control** systems: Git
- **Development tools**: Visual Studio Code
***

## 5. Code Example
Below is a sample code in Python:

```
public static string PigIt(string str)
            {
                if (string.IsNullOrEmpty(str))
                {
                    throw new ArgumentNullException(nameof(str));
                }

                string word = string.Empty;
                string result = string.Empty;

                for (int i = 0; i < str.Length; i++)
                {
                    if (i == str.Length || str[i] == ' ')
                    {
                        if (word.Length == 0 && i != str.Length)
                        {
                            result = string.Concat(result, str[i]);
                        }
                        else
                        {
                            string letter = $"{word[0]}ay";

                            word = word[1..];

                            word = string.Concat(word, letter);

                            result = string.Concat(result, word);

                            word = string.Empty;
                        }
                    }
                    if (i != str.Length)
                    {
                        if (char.IsLetterOrDigit(str[i]))
                        {
                            word = string.Concat(word, str[i]);

                            if (i == str.Length - 1)
                            {
                                string letter = $"{word[0]}ay";

                                word = word[1..];

                                word = string.Concat(word, letter);

                                result = string.Concat(result, word);
                            }
                        }
                        else
                        {
                            result = string.Concat(result, str[i]);
                        }
                    }
                }
                return result;
            }
```
***