# mend
birthday queen
import pyfiglet
from colorama import Fore, Style, init
import time

init(autoreset=True)  # Өнгийг автоматаар default болгож өгнө

# Хэрэглэгчийн мэдээлэл
нэр = Uyanga
нас = 18

# ASCII том гарчиг
гарчиг = pyfiglet.figlet_format("Happy Birthday!")
print(Fore.MAGENTA + гарчиг)

# Гоёмсог мэндчилгээ
print(Fore.YELLOW + "="*60)
print(Fore.CYAN + f"🎉  Төрсөн өдрийн мэнд хүргэе, {нэр} аа! Та {нас} настай боллоо! 🎂")
print(Fore.YELLOW + "-"*60)

print(Fore.GREEN + f"""
Таны энэ өдөр аз жаргал, инээд хөөрөөр дүүрэн байх болтугай! 🎈
    🌟 Эрүүл энх байж, хүсэл мөрөөдлөө биелүүлээрэй 🌟
    💖 Танд амжилт, хайр, баяр хөөр дүүрэн байг 💖
""")

print(Fore.YELLOW + "="*60)
print(Fore.BLUE + "🎁 Мэндчилгээ илгээгдэж байна", end="")
for _ in range(3):
    print(".", end="", flush=True)
    time.sleep(0.7)
print("\n" + Fore.GREEN + "✅ Амжилттай илгээгдлээ! 🎊")
print(Fore.YELLOW + "="*60)
