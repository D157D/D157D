# Crazy Lobby

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

Developed by a team of 3 members


# StreetBeat 🎧🔥

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
* **UI**: Menu, HUD, pause system
* **Environment**: Map, lighting, assets
* **Effects**: Neon glow, particle, feedback
* **Core**: GameManager, input handling

## Team

Developed by a team of 3 members
