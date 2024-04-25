from flask import Flask, render_template_string

app = Flask(__name__)

@app.route('/')
def hello():
    return render_template_string('''
    <div style="text-align: center;">
        <h2>𝐇𝐞𝐥𝐥𝐨 𝐭𝐡𝐞𝐫𝐞, 𝐟𝐞𝐥𝐥𝐨𝐰 &lt;𝚍𝚎𝚟𝚎𝚕𝚘𝚙𝚎𝚛𝚜/&gt;! <img src="https://github.com/ABSphreak/ABSphreak/blob/master/gifs/Hi.gif" width="30"></h2>
    </div>
    ''')

if __name__ == '__main__':
    app.run(debug=True)


- 👋 Hi, I’m @VitorSM03____
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
VitorSM03/VitorSM03 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
