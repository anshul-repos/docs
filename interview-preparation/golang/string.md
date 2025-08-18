
•     convert to lowecase
    str := strings.ToLower(s)


• string.Fields

    
• strings.Split
    
•  convert Int to String
        Strconv.Itoa()
        
• A byte only holds ASCII characters (like A–Z, 0–9), because it's 8 bits.
    
    But strings in Go can have Unicode characters (like ✓, あ, 😀), and these might need more than 1 byte.
    So when you loop over a string like this:
        for _, s:= range str {}
    "s" is automatically a rune, not a byte because Go wants to make sure you're working with full characters, not pieces of them.