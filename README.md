# Summoning Chess · Cờ Vua Triệu Hồi

**Play / Chơi ngay:** https://midunguyeniu.github.io/SummoningChess/

*Game made by Gary Duc Nguyen · Game được làm bởi Gary Duc Nguyen*

🇬🇧 [English](#english) · 🇻🇳 [Tiếng Việt](#tiếng-việt)

---

## English

A chess variant played in the browser. Each side starts with only a **King**. Collect resources, **summon** new pieces next to your King, and **capture the enemy King** to win. Play against the AI or with 2 players on one device.

### Goal

Win by **capturing the enemy King**, or by **checkmate** (see below).

### Setup

- 8×8 board. White King on e1, Black King on d8. Each side starts with just 1 King.
- Resources (meat, stone, rice) are placed randomly on the board: **16 meat, 8 stone, 8 rice**.
- White moves first.

### Each turn, choose 1 of 2

1. **Move** one of your pieces. Pieces move like in traditional chess. The Pawn may also move 2 squares on its first move, and may **step back 1 square** (it never captures backwards, and there is no promotion).
2. **Summon** a new piece (Pawn, Rook, Knight, Bishop or Queen) onto an empty square next to your King, paying with resources. Summoning takes your whole turn.

### Resources

- **Only the King** collects resources, by moving onto their square.
- Other pieces can pass through a resource square but **cannot stop** on it. The exception is the **Pawn**: it may stand on a resource square, and the resource stays under it (a King that captures that Pawn collects it).
- Both sides' resource counters are always public.
- When a piece (not a King) is captured, the resources spent summoning it **respawn at random** on the board.

### Summon costs

| Piece | Cost |
|---|---|
| Pawn | 1 meat |
| Rook | 1 stone + 1 meat |
| Knight | 1 meat + 1 rice |
| Bishop | 1 rice + 1 stone |
| Queen | 1 stone + 1 rice + 1 meat |

### King safety, check and checkmate

- A **human player's King cannot step onto a square the opponent can capture right away.** The AI's King and all other pieces have no such limit.
- When a King is under threat, a **CHECK** label shows on it.
- If the side to move has **no way left to save its King** (no move, capture or summon that stops the threat), it is **CHECKMATE** and the game ends immediately.

### Other rules

- If a side has no possible action, it skips its turn. If neither side has any, the game is a **draw**.
- Moves are counted in full moves, as in chess: the number goes up after Black has moved.

### Game modes

- **Opponent:** play against the AI, or 2 players on one device.
- **Your side:** White (moves first) or Black.
- **AI difficulty** (how many moves it looks ahead): ★ (1), ★★ (2), ★★★ (3), ★★★★ (6), ★★★★★ (10). Higher levels may take a few seconds per move.
- **Board theme:** 4 color themes. Language: Vietnamese or English (flag buttons).

---

## Tiếng Việt

Một biến thể cờ vua chơi trên trình duyệt. Mỗi bên bắt đầu chỉ với **1 Vua**. Hãy thu thập tài nguyên, **triệu hồi** quân mới ngay cạnh Vua và **ăn Vua đối phương** để thắng. Chơi với AI hoặc 2 người chung một máy.

### Mục tiêu

Thắng bằng cách **ăn Vua đối phương**, hoặc **chiếu hết** (xem bên dưới).

### Bố trí đầu ván

- Bàn 8×8. Vua Trắng ở e1, Vua Đen ở d8. Mỗi bên bắt đầu chỉ có 1 Vua.
- Tài nguyên (thịt, đá, gạo) rải ngẫu nhiên trên bàn: **16 thịt, 8 đá, 8 gạo**.
- Trắng đi trước.

### Mỗi lượt chọn 1 trong 2

1. **Đi quân**: đi một quân của mình. Các quân đi như cờ vua truyền thống. Tốt còn được đi 2 ô ở nước đầu tiên và được **lùi 1 ô** (không ăn quân khi lùi, không có phong cấp).
2. **Triệu hồi**: đặt một quân mới (Tốt, Xe, Mã, Tượng hoặc Hậu) vào ô trống cạnh Vua, trả bằng tài nguyên. Triệu hồi tốn trọn 1 lượt.

### Tài nguyên

- **Chỉ Vua** mới ăn được tài nguyên, bằng cách đi vào ô có tài nguyên.
- Quân khác đi xuyên qua ô tài nguyên được nhưng **không dừng lại** trên ô đó. Ngoại lệ là **Tốt**: Tốt được đứng trên ô tài nguyên, tài nguyên vẫn nằm yên dưới Tốt (Vua ăn được Tốt đó sẽ thu luôn tài nguyên).
- Bảng đếm tài nguyên của cả hai bên luôn hiển thị công khai.
- Khi một quân (không phải Vua) bị ăn, số tài nguyên đã dùng để triệu hồi quân đó sẽ **sinh lại ngẫu nhiên** trên bàn.

### Giá triệu hồi

| Quân | Giá |
|---|---|
| Tốt | 1 thịt |
| Xe | 1 đá + 1 thịt |
| Mã | 1 thịt + 1 gạo |
| Tượng | 1 gạo + 1 đá |
| Hậu | 1 đá + 1 gạo + 1 thịt |

### An toàn của Vua, chiếu và chiếu hết

- **Vua của người chơi không được đi vào ô mà đối thủ ăn được ngay.** Vua của AI và các quân khác không bị giới hạn này.
- Khi Vua bị đe doạ, trên Vua hiện nhãn **CHECK**.
- Nếu bên tới lượt **không còn cách nào cứu Vua** (không có nước đi, ăn quân hay triệu hồi nào chặn được mối đe doạ) thì là **CHIẾU HẾT** và ván kết thúc ngay.

### Luật phụ

- Bên nào không còn hành động nào thì bỏ lượt. Nếu cả hai bên đều không còn thì **hoà**.
- Nước đi được đếm theo nước đi đôi như trong cờ vua: số tăng lên sau khi Đen đi xong.

### Chế độ chơi

- **Đối thủ:** chơi với AI, hoặc 2 người chung một máy.
- **Bạn cầm quân:** Trắng (đi trước) hoặc Đen.
- **Độ khó của AI** (số nước AI tính trước): ★ (1), ★★ (2), ★★★ (3), ★★★★ (6), ★★★★★ (10). Mức cao có thể mất vài giây mỗi nước.
- **Màu bàn cờ:** 4 theme. Ngôn ngữ: Tiếng Việt hoặc English (nút cờ).
