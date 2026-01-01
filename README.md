# Maisha

**Life-saving messages designed for print, SMS, and radio.**

**[maisha.work](https://maisha.work)**

Maisha is a collection of short, practical health and safety messages optimized for low-infrastructure contexts. The messages are designed to travel through paper, voice, text message, and community radio—channels that work when internet and electricity are unreliable.

## About

Maisha exists to spread essential knowledge where formal systems are weak, absent, overloaded, or distrusted. Each message is written to be:

- Understood on first reading
- Easy to remember
- Safe to follow without professional supervision
- Short enough to fit in an SMS

The name "Maisha" comes from the Swahili word for "life."

## Website Structure

```
index.html       # Home page
messages.html    # Life message library
print.html       # Print center and guidance
spread.html      # How to share messages
about.html       # Philosophy and approach
contribute.html  # How to help
styles.css       # Stylesheet
```

## Local Development

This is a static site with no build process. To view locally:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Or simply open index.html in a browser
```

## Contributing

Contributions are welcome:

- **Translate** a message into another language
- **Improve clarity** of existing messages
- **Suggest** new life-saving messages
- **Report** issues with the website

See [contribute.html](contribute.html) for guidelines.

## Principles

- **Safety over completeness** — A safe but incomplete message beats a complete but risky one
- **Usefulness over universality** — Local relevance matters more than global reach
- **Lightweight by design** — No registration, no funding requirements, no organizational overhead

## License

[CC0 1.0 Universal](LICENSE) — No rights reserved. Maisha messages are free to use, share, print, and translate. They belong to whoever finds them useful.
