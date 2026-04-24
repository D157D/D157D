# Crazy Lobby (3/2026 - 4/2026)

![Lobby Preview](/CrazyLobby.png)

Crazy Lobby is a multiplayer party game inspired by chaotic obstacle-course gameplay where players compete to survive and reach the finish line.

## Overview

Crazy Lobby focuses on fast-paced, physics-based gameplay combined with a simple but functional lobby system. Players can quickly join matches, create rooms, and interact before entering the game.

## Features

* Lobby system with player profile and character selection
* Quick Play matchmaking
* Room system (Join / Create by ID)
* Real-time multiplayer gameplay
* Physics-based obstacles and interactive maps
* Basic chat system in lobby

## Gameplay

![Gameplay](/GamePlay.png)

Players spawn into dynamic maps filled with traps, moving platforms, and hazards. The objective is to survive and reach the goal before other players.

## Lobby & UI

![UI](Menu-CrazyLobby.png)

The lobby allows players to select characters, chat, and manage matchmaking before entering a game session.

## Tech Stack

* Unity (Client)
* C#
* ASP.NET Core Web API (Lobby, authentication, matchmaking)
* PhotonFusion (real-time gameplay synchronization)

## Project Structure

* Client: Unity project (UI, gameplay systems, animations)
* Server: Web API + WebSocket server
* Assets: Characters, UI elements, environment

## Status

Prototype / Demo with core systems implemented (lobby, basic gameplay, multiplayer sync)

## Team

Developed by a team of 2 members


# StreetBeat 🎧🔥 (12/2025 - 2/2026)

![Menu Preview](/StreetBeat.png)

StreetBeat là một game **endless runner kết hợp nhịp điệu (rhythm)**, nơi người chơi điều khiển nhân vật chạy qua các con phố đầy màu sắc và né tránh chướng ngại vật theo nhịp beat của âm nhạc.

## Overview

StreetBeat tập trung vào gameplay **nhanh, phản xạ cao** kết hợp với hiệu ứng âm nhạc và ánh sáng neon. Người chơi phải di chuyển chính xác theo lane, né vật cản và tận dụng nhịp điệu để đạt điểm số cao nhất.

## Features

* Gameplay endless runner theo lane (trái / giữa / phải)
* Hệ thống score và multiplier (combo theo nhịp)
* Nhiều map khác nhau (city, beach, neon night, ...)
* Obstacle đa dạng với hướng chỉ dẫn trực quan
* Hiệu ứng ánh sáng neon + particle theo beat
* UI đơn giản, tối ưu cho mobile
* Pause / Resume trong gameplay

## Gameplay

![Gameplay](/M1.png)

Người chơi điều khiển nhân vật chạy liên tục về phía trước.  

**Nhiệm vụ chính:**
* Né chướng ngại vật (trái / phải / nhảy / trượt)
* Thu thập điểm và duy trì combo
* Phản xạ nhanh theo tốc độ game tăng dần

**Độ khó tăng dần khi:**
* Tốc độ tăng
* Obstacle xuất hiện dày hơn
* Yêu cầu xử lý chính xác hơn

## Maps & Visual Style

![Maps](/M2.png)

StreetBeat có nhiều môi trường khác nhau:

* 🌆 Neon City (ban đêm, ánh sáng rực rỡ)
* 🏝️ Beach (ban ngày, vibe thư giãn)
* 🏙️ Urban Street (phố hiện đại)

Mỗi map có:
* Màu sắc riêng
* Lighting khác nhau
* Cảm giác nhịp điệu riêng biệt
<!-- 
## UI & Menu

![UI]()

Menu chính bao gồm:

* **Levels**: chọn map / chế độ chơi  
* **LeaderBoard**: bảng xếp hạng điểm số  
* **Setting**: cài đặt âm thanh, game  

UI được thiết kế đơn giản, rõ ràng, tối ưu cho mobile. -->

## Tech Stack

* Unity (Game Engine)
* C#
* Mobile Platform (Android)
* Animator + Particle System
* Object Pooling (tối ưu performance)

## Project Structure

* **Gameplay**: Player controller, obstacle system, score
* **UI**: Menu, HUD, BXH, Pause, Setting
* **Environment**: Map, lighting, assets
* **Effects**: Neon glow, particle, feedback
* **Core**: GameManager, input handling

## Team

Developed by a team of 3 members


# Relic Seeker 🧭🏛️ (9/2025 - 11/2025)

![Menu Preview](/Relic%20Seeker.png)

**Relic Seeker** là một tựa game giải đố phiêu lưu (puzzle-adventure) trên di động. Người chơi sẽ vào vai một nhà thám hiểm vượt qua những hầm ngục cổ xưa, giải mã các cơ quan phức tạp và né tránh quái vật để tìm kiếm cổ vật quý giá.

## Overview

Game tập trung vào lối chơi **logic grid-based** (di chuyển theo ô). Mỗi bước đi đều cần sự tính toán để kích hoạt đúng cần gạt, mở đường và tránh khỏi tầm mắt của những sinh vật canh giữ hầm ngục.

## Features

* **Giải đố theo ô (Grid-based):** Di chuyển chiến thuật trên bản đồ được chia ô.
* **Cơ chế tương tác:** Hệ thống đòn bẩy (Levers), hố sụt (Pits) và cổng dịch chuyển (Portals).
* **Kẻ thù thông minh:** Quái vật (Nhện khổng lồ) có quy luật di chuyển riêng, thách thức khả năng quan sát.
* **Hệ thống thu thập:** Thu thập đá quý (Gems) để tối ưu hóa điểm số qua mỗi màn chơi.
* **Đồ họa Low-poly:** Phong cách 3D tối giản, hiệu năng cao, phù hợp với nhiều dòng máy mobile.
* **Cấp độ đa dạng:** Hàng chục màn chơi với độ khó tăng dần và các loại địa hình mới.

## Gameplay

![Gameplay](/lv4.png)

Người chơi điều khiển nhân vật chính tìm đường đến cổng thoát hiểm rực rỡ cuối mỗi hầm ngục.

**Nhiệm vụ chính:**
* **Kích hoạt cơ quan:** Tìm và gạt các cần điều khiển để lấp hố hoặc mở lối đi bí mật.
* **Tránh cạm bẫy:** Quan sát nhịp di chuyển của nhện để đi qua an toàn.
* **Thu thập Ruby:** Gom đủ số lượng đá quý đỏ để đạt hạng cao nhất.

**Yếu tố thử thách:**
* Càng lên level cao (Level 17, 19...), số lượng kẻ thù và cơ quan xuất hiện đồng thời, đòi hỏi trình tự xử lý chính xác.

## Maps & Visual Style

![Maps](/lv17.png)
![Maps](/lv19.png)
Relic Seeker sử dụng tông màu ấm và phong cách cổ điển:
* **Ancient Tomb:** Bối cảnh đá tảng, bụi bặm và huyền bí.
* **Mystic Ruins:** Sự kết hợp giữa tàn tích cổ và thảm thực vật xanh mướt.
* **Atmospheric Lighting:** Hiệu ứng ánh sáng từ cổng dịch chuyển và các vật phẩm phát sáng tạo điểm nhấn.

## UI & Menu

![UI](/Menu.png)

Giao diện tối giản và tập trung vào trải nghiệm người dùng:
* **Main Menu:** Logo cách điệu, nút Play trung tâm với icon viên kim cương.
* **Ranking:** Theo dõi thứ hạng người chơi.
* **Settings:** Tùy chỉnh âm thanh và cấu hình.
* **In-game UI:** Hiển thị số màn chơi và các nút chức năng hỗ trợ (Settings, Reset).

## Tech Stack

* **Unity Engine:** Nền tảng phát triển chính.
* **C#:** Xử lý logic gameplay và hệ thống Event.
* **Mobile Platform:** Tối ưu hóa cho Android (hỗ trợ các tỉ lệ màn hình dài/notch).
* **Object Pooling:** Tối ưu hóa hiệu năng khi load các prefab địa hình và vật phẩm.

## Project Structure

* **Core**: Scripts quản lý game (GameManager, LevelManager).
* **Player**: Controller điều khiển nhân vật và hệ thống Input.
* **Mechanics**: Logic cho cần gạt, cổng dịch chuyển, quái vật.
* **Environment**: Model 3D, Prefabs địa hình và hiệu ứng ánh sáng.
* **UI**: Scripts quản lý menu và các lớp giao diện.

## Status

**Prototype Stage:**
- Hoàn thiện core di chuyển và tương tác cơ bản.
- Thiết kế 25 levels demo.
- Tích hợp hệ thống Save/Load.

## Team

Developed by a team of 3 members.
