# Hi there! 👋

Welcome to my GitHub profile! I'm thrilled to have you here.

## About Me

- 🎓 **Student at [42 coding school](https://www.42.fr/)**
- 💻 **Languages:** C, Bash (currently learning Python)
- 🌱 **Interests:** Cybersecurity, Artificial Intelligence, Backend Development
- 📜 **Certification:** "I am currently progressing through the 42 curriculum, which equips students with essential coding skills and a broad range of soft skills. I have completed several projects up to 'minishell,' marking nearly halfway through the core program."

## GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=Cloneg7&show_icons=true&locale=en&layout=compact&theme=dark&bg_color=000000&text_color=ffffff" alt="Top Languages" />
  <img src="https://github-readme-stats.vercel.app/api?username=Cloneg7&show_icons=true&locale=en&theme=dark&bg_color=000000" alt="GitHub Stats" />
</div>

## Contributions

![GitHub Contributions](https://github-readme-streak-stats.herokuapp.com/?user=Cloneg7&theme=dark&background=000000&ring=ffffff&fire=ffffff&currStreakLabel=ffffff)

## 📣 How to Contact Me

_will be added soon..._


-------------


# Hi there! 👋

Welcome to my GitHub profile! I'm thrilled to have you here.

## About Me

- 🎓 **Student at [42 coding school](https://www.42.fr/)**
- 💻 **Languages:** C, Bash (currently learning Python)
- 🌱 **Interests:** Cybersecurity, Artificial Intelligence, Backend Development
- 📜 **Certification:** "I am currently progressing through the 42 curriculum, which equips students with essential coding skills and a broad range of soft skills. I have completed several projects up to 'minishell,' marking nearly halfway through the core program."

## Python I/O Example

Here's a simple Python script that demonstrates basic file I/O operations. This script reads content from a file and writes it to another file:

```python
# Python I/O Example

# Function to read from a file
def read_file(file_path):
    with open(file_path, 'r') as file:
        content = file.read()
    return content

# Function to write to a file
def write_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)

# Main function
def main():
    input_file = 'input.txt'
    output_file = 'output.txt'
    
    # Read from input file
    content = read_file(input_file)
    print(f"Read from {input_file}:")
    print(content)
    
    # Write to output file
    write_file(output_file, content)
    print(f"Content written to {output_file}")

if __name__ == "__main__":
    main()
