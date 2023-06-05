## Problema C

# Password Strength

Arquivo fonte: forcasenha.{ c | cpp | java | py }

Autor: Erico de Souza Veriscimo (Fatec Mogi das Cruzes)

Elenilson and Erinilson are developing the new InterFatecs Programming Constest portal. They are currently having difficulty writing code that validates user registration passwords. They found out that you always participate in programming contests and asked for your help. To do so, you must meet the following criteria:

- A password cannot have punctuation characters (.,!?;:), accent (áéíóúâêôãõàçÁÉÍÓÚÂÊÔÃÕÀÇ), or spaces;

- A password must contain at least one uppercase letter, one lowercase letter, and one number;

- A password must be between 6 and 15;

- And canno yet contain values in sequence, such as "01", "ab" or "AB".

Your task is: given a password, determine if it is valid or invalid considering the criteria presented.

### Input

An entry contain $S\ (1 \le length(S) \le 20)$ corresponding to the password entered by the user.

### Output

The output contains a single line with the phrase $True.$ (with the first letter capitalized and the point at the end) if the password meets criteria, or $False.$ (with the first letter capitalized and the point at the end) if contrary. Finish with a line break.

|Example of Input 1|Example of Output 1|
|------------------|-------------------|
|abCE13245         |False.             |

|Example of Input 2|Example of Output 2|
|------------------|-------------------|
|aceF13592         |True.              |