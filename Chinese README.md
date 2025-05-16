你好，我想要建立一個 Line Bot。我想要用它來買賣各種產品。請為我修改以下代碼，以便我能實現包含以下內容的9個多樣化類別：1. 電子產品和小工具：智能手機、無線耳機、智能手錶 2. 時尚與服裝：T恤、運動鞋、手提包 3. 美容和個人護理：面部精華液、口紅、洗髮水 4. 家居和廚房產品：咖啡機、抱枕、收納盒 5. 食品和飲料：特色咖啡豆、美食餅乾、精釀啤酒、六罐裝 6. 健康與健身：瑜伽墊、蛋白粉、健身追蹤器 7. 玩具和愛好：積木、繪畫套裝、桌遊 8. 配飾：手機殼、項鍊、棒球帽 9. 寵物產品：狗糧、貓玩具、寵物床

這意味著當顧客首次進入機器人時，他們應該先輸入"Menu"。然後菜單包括Our Product、FAQ和Contact Us。
在FAQ部分，應包括以下內容，該部分由5個部分組成（一般機器人互動、產品信息、訂購和付款、運輸和交付以及退貨和支持）：

一般機器人互動：

問：如何開始購買？
答：通常，如果有"Menu"按鈕，您可以通過輸入關鍵詞開始。您也可以瀏覽類別或使用關鍵詞搜索特定商品。
問：我可以從這個機器人購買什麼？
答：此機器人提供[提及產品類型]。您可以瀏覽我們的產品或詢問特定商品。
問：如何導航機器人的選項？
答：機器人通常提供按鈕、菜單或關鍵詞命令，您可以使用這些來導航。請按照機器人提供的提示操作。


產品信息：

問：如何查看產品詳情？
答：當您看到感興趣的產品時，通常可以點擊它或輸入諸如"details"後跟產品名稱或編號的命令。
問：我可以看到產品的圖片嗎？
答：是的，機器人通常會與產品描述一起顯示圖片。
問：我如何知道產品是否有庫存？
答：機器人通常會在其詳情頁面上指示產品的可用性。如果庫存不足，它可能會說明。


訂購和付款：

問：如何將商品添加到購物車？
答：通常有一個"Add to Cart"按鈕或類似"add [產品名稱] to cart"的關鍵詞命令。
問：如何查看我的購物車？
答：您通常可以通過點擊"Cart"圖標或輸入"view cart"等命令來查看您的購物車。
問：您接受哪些付款方式？
答：我們目前接受[列出接受的付款方式，例如信用卡、借記卡、PayPal、移動支付選項]。


運輸和交付：

問：運費是多少？
答：運費根據目的地和訂單的重量/尺寸而有所不同。在完成購買前，您通常可以在結賬過程中看到運費。
問：您是否運送到[我的位置]？
答：請在結賬過程中提供您的位置，以查看我們是否運送到那裡。[或者，如果有運送地點列表，請提及它。]
問：收到訂單需要多長時間？
答：交付時間根據您的位置和所選的運輸方式而有所不同。您通常會在結賬時看到預計的交付時間範圍。


退貨和支持：

問：您的退貨政策是什麼？
答：對於大多數物品，只要它們保持原始狀態，我們提供[數字]天的退貨政策。詳情請查看我們的完整退貨政策[如果機器人可以鏈接到它或提供更多信息]。
問：如何發起退貨？
答：要發起退貨，請通過[提及聯繫方式，例如"Contact Us"按鈕或特定命令]聯繫我們的客戶支持。
問：如果我有問題或需要幫助怎麼辦？
答：您可以通過[提及聯繫方式，例如點擊"Support"按鈕或輸入"help"]聯繫我們的客戶支持團隊。我們在這裡為您提供幫助。


Contact Us部分應包括電話號碼、電子郵件和地址：
886912345678

電子郵件：Admin@linebot.com

台灣雲林縣斗六市龍潭路

此外，當顧客點擊Our Product時，應在9個單獨的框中顯示9個類別，每個框應顯示該類別下的3個產品。當我們點擊每個產品子類別選項時，它應顯示一個包括：產品名稱、產品價格、關於產品的簡短描述以及最後產品鏈接的列表。這樣我們就可以看到子類別中的產品列表。還有產品2和3等...


產品包括：

1. 電子產品和小工具：

子集：智能手機
產品名稱：Galaxy Ultra S25
產品價格：$1299
簡短描述：最新旗艦智能手機，配備高解析度相機和快速處理器。
購買鏈接：[鏈接]
子集：無線耳機
產品名稱：NoiseCancelling Pro Buds
產品價格：$249
簡短描述：高級頭戴式耳機，具有主動降噪和長電池壽命。
購買鏈接：[鏈接]
子集：智能手錶
產品名稱：FitTrack Pro 7
產品價格：$199
簡短描述：先進的智能手錶，具有心率監測、GPS和睡眠追蹤功能。
購買鏈接：[鏈接]
2. 時尚與服裝：

子集：女士上衣
產品名稱：Flowy Linen Blouse
產品價格：$59
簡短描述：透氣且時尚的亞麻襯衫，適合溫暖天氣。
購買鏈接：[鏈接]
子集：男士鞋履
產品名稱：Leather Casual Sneakers
產品價格：$89
簡短描述：舒適耐用的皮革休閒鞋，適合日常穿著。
購買鏈接：[鏈接]
子集：時尚配飾
產品名稱：Woven Straw Tote Bag
產品價格：$45
簡短描述：時尚草編手提包，非常適合夏季外出。
購買鏈接：[鏈接]
3. 美容和個人護理：

子集：護膚
產品名稱：Hyaluronic Acid Serum
產品價格：$35
簡短描述：保濕精華液，有助於豐盈和滋潤肌膚。
購買鏈接：[鏈接]
子集：化妝品
產品名稱：Long-Lasting Matte Lipstick
產品價格：$22
簡短描述：高顏料霧面口紅，可持續數小時。
購買鏈接：[鏈接]
子集：護髮
產品名稱：Nourishing Hair Mask
產品價格：$28
簡短描述：深層調理髮膜，修復和滋潤乾燥的頭髮。
購買鏈接：[鏈接]
4. 家居和廚房產品：

子集：小型廚房電器
產品名稱：Electric Kettle with Temperature Control
產品價格：$65
簡短描述：不鏽鋼電熱水壺，具有精確的溫度設置。
購買鏈接：[鏈接]
子集：家居裝飾
產品名稱：Set of Decorative Throw Pillows
產品價格：$40
簡短描述：兩個時尚的抱枕，可提升您的客廳裝飾。
購買鏈接：[鏈接]
子集：廚房儲物
產品名稱：Airtight Food Storage Containers (Set of 5)
產品價格：$30
簡短描述：五個密封容器套裝，保持食物新鮮。
購買鏈接：[鏈接]
5. 食品和飲料：

子集：咖啡和茶
產品名稱：Organic Fair Trade Ground Coffee
產品價格：$15（每袋）
簡短描述：香濃有香氣的有機公平貿易研磨咖啡。
購買鏈接：[鏈接]
子集：零食
產品名稱：Gourmet Dark Chocolate Sea Salt Caramels
產品價格：$12（每盒）
簡短描述：佐以海鹽的誘人黑巧克力太妃糖。
購買鏈接：[鏈接]
子集：飲料（非酒精）
產品名稱：Sparkling Natural Fruit Juice (Pack of 6)
產品價格：$18
簡短描述：清爽的天然果汁氣泡飲料，不含添加糖。
購買鏈接：[鏈接]
6. 健康與健身：

子集：健身器材
產品名稱：Adjustable Resistance Bands Set
產品價格：$25
簡短描述：五個不同阻力等級的彈力帶套裝，用於多功能鍛煉。
購買鏈接：[鏈接]
子集：營養補充劑
產品名稱：Plant-Based Protein Powder (Vanilla)
產品價格：$45（每罐）
簡短描述：素食蛋白粉，非常適合鍛煉後恢復。
購買鏈接：[鏈接]
子集：健康產品
產品名稱：Essential Oil Diffuser
產品價格：$30
簡短描述：超聲波擴散器，用於在空間中散發舒緩精油香氣。
購買鏈接：[鏈接]
7. 玩具和愛好：

子集：教育玩具
產品名稱：STEM Building Kit for Kids
產品價格：$49
簡短描述：教授基本工程原理的有趣拼搭套件。
購買鏈接：[鏈接]
子集：藝術與手工
產品名稱：Deluxe Acrylic Paint Set (24 Colors)
產品價格：$35
簡短描述：藝術家用的高質量24色鮮艷丙烯顏料套裝。
購買鏈接：[鏈接]
子集：遊戲
產品名稱：Strategy Board Game for Adults
產品價格：$40
簡短描述：適合2-4名玩家的引人入勝的策略桌遊。
購買鏈接：[鏈接]
8. 配飾：

子集：手機配件
產品名稱：Fast Charging USB-C Cable
產品價格：$19
簡短描述：適用於您的設備的耐用且快速充電的USB-C線。
購買鏈接：[鏈接]
子集：珠寶
產品名稱：Sterling Silver Pendant Necklace
產品價格：$69
簡短描述：適合日常佩戴的優雅純銀吊墜項鍊。
購買鏈接：[鏈接]
子集：包袋
產品名稱：Lightweight Backpack for Travel
產品價格：$75
簡短描述：舒適且寬敞的背包，非常適合旅行。
購買鏈接：[鏈接]
9. 寵物產品：

子集：寵物食品
產品名稱：Premium Grain-Free Dry Dog Food (Chicken)
產品價格：$55（每袋）
簡短描述：以雞肉為主要成分的高質量無穀物狗糧。
購買鏈接：[鏈接]
子集：寵物玩具
產品名稱：Interactive Puzzle Toy for Cats
產品價格：$28
簡短描述：為貓提供心智刺激的互動益智玩具。
購買鏈接：[鏈接]
子集：寵物護理用品
產品名稱：Orthopedic Pet Bed for Large Dogs
產品價格：$120
簡短描述：舒適的骨科床墊，支撐大型犬的關節。
購買鏈接：[鏈接]

順便說一下，我對編程一無所知，也不懂代碼。請編寫完整的代碼，以便我可以直接複製和粘貼。（我只知道如何找到並粘貼Ngrok Token、Channel access token和Channel secret）。我的環境是Google Colab。請記住，LINE 允許輪播按鈕的標籤最多包含 20 個字元。

from flask import Flask, request, abort
from linebot import LineBotApi, WebhookHandler
from linebot.exceptions import InvalidSignatureError
from linebot.models import *
from pyngrok import ngrok
# === Your LINE Channel credentials ===
LINE_CHANNEL_ACCESS_TOKEN = 'll65x4KXrRTC/BhrlsLvkJpAaGMHA5zkDzFSsKjEOshmCrdvE5Zq4kfw6CMteyoKBqJfKFuMGnPF/iE9RZYLCLVTNAsuvFYXHde+Iptxg+Owlg8kwIR9Bd1BN/zt1Vqp0R7O8n4LNxNL5m4uFF9PLQdB04t89/1O/w1cDnyilFU='
LINE_CHANNEL_SECRET = '1ca2691e7185f7a91e1742d014f82b44'

# Set up ngrok with your token (for persistent tunnels)
!ngrok authtoken '2wB6u31MuSCi9Procs5EUegUF50_4XrNKQCQ1GXr1Ptst2gRm'  # Use your actual ngrok token here!

app = Flask(__name__)
line_bot_api = LineBotApi(LINE_CHANNEL_ACCESS_TOKEN)
handler = WebhookHandler(LINE_CHANNEL_SECRET)

@app.route("/callback", methods=['POST'])
def callback():
    signature = request.headers['X-Line-Signature']
    body = request.get_data(as_text=True)

    try:
        handler.handle(body, signature)
    except InvalidSignatureError:
        abort(400)

    return 'OK'

@handler.add(MessageEvent, message=TextMessage)
def handle_message(event):
    text = event.message.text.lower()

    if text in ['start', 'menu']:
        buttons_template = TemplateSendMessage(
            alt_text='Main Menu',
            template=ButtonsTemplate(
                title='Department Info',
                text='Please choose an option:',
                actions=[
                    MessageAction(label='📋 Department Info ', text='info'),
                    MessageAction(label='📧 Director Email', text='email'),
                    MessageAction(label='📍 Location', text='location'),
                ]
            )
        )
        line_bot_api.reply_message(event.reply_token, buttons_template)

    elif text == 'info':
        line_bot_api.reply_message(event.reply_token, TextSendMessage(
            text="Our department specializes in Computer Science and offers degrees from undergraduate to Ph.D."
        ))
    elif text == 'email':
        line_bot_api.reply_message(event.reply_token, TextSendMessage(
            text="You can contact the department director at: director@university.edu"
        ))
    elif text == 'location':
        line_bot_api.reply_message(event.reply_token, TextSendMessage(
            text="The department is located at: Building B, 2nd Floor, Room 203, Main Campus."
        ))
    else:
        line_bot_api.reply_message(event.reply_token, TextSendMessage(
            text="Hi! I hope had a great day so far ,Please type 'menu' to see options."
        ))

# Start ngrok tunnel
public_url = ngrok.connect(5000)
print(f"🌐 Public URL: {public_url}/callback")

# Start Flask app
app.run()