import discord
from discord.ext import commands

intents = discord.Intents.default()
intents.message_content = True

bot = commands.Bot(command_prefix='$', intents=intents)

@bot.event
async def on_ready():
    print(f'We have logged in as {bot.user}')

@bot.command()
async def hello(ctx):
    await ctx.send(f'Hi! I am a bot {bot.user}!')

@bot.command()
async def bro(ctx):
    await ctx.send(f'bro! {bot.user}, how are you?')


@bot.command()
async def heh(ctx, count_heh = 5):
    await ctx.send("he" * count_heh)

bot.command()
async def hah(ctx, count_hah = 5):
    await ctx.send("ha" * count_hah)

@bot.command()
async def mem(ctx):
    with open('m2l1\slide3.jpg', 'rb') as f:
        # Mari simpan file perpustakaan/library Discord yang dikonversi dalam variabel ini!
        picture = discord.File(f)
   # Kita kemudian dapat mengirim file ini sebagai tolok ukur!
    await ctx.send(file=picture)

@bot.command()
async def animals(ctx):
    with open('monkey puppet.jpg', 'rb') as f:
        picture = discord.File(f)
    await ctx.send(file=picture)

@bot.command()
async def cara_mengurangi_sampah(ctx):
    await ctx.send('''1.	Memisahkan Sampah Sesuai Jenisnya. ...
2.	Melakukan Zero Waste. ...
3.	Membuat Pupuk dari Sampah Organik. ...
4.	Membersihkan Tempat Sampah Setiap Hari. ...
5.	Melakukan Daur Ulang Pada Sampah Anorganik.
''')
@bot.command()
async def cara_menghasilkan_cuan(ctx):
    await ctx.send('''dengan mengubah sampah sekitar rumah menjadi barang yang bermanfaat bagi masyarakat
''')
    
@bot.command()
async def cara_mendaur_ulang_sampah(ctx):
    await ctx.send('''Koleksi. Langkah pertama dalam proses daur ulang sampah yaitu mengumpulkan material atau plastik yang akan didaur ulang. ...
2. Sortir. ...
Pencucian. ...
4. Resizing. ...
Pemilahan Plastik. ...
6. Penggabungan.''')
    
