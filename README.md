# COFFSEEKER
資展會前端工程師養成班第42期 期末專題  iSpan-MFEE42

- demo video：https://youtu.be/OW6MTzekUec
- 企劃書：https://docs.google.com/presentation/d/1Hp83zj3mIZ1ZkqcBvtAvwh-ieWKb310XrsM5Di-LGSo/edit?usp=sharing
## 作品說明
「COFFSEEKER」是一家精選來自世界各地咖啡豆的品牌。我們深知現代人對咖啡風味的精緻要求，因此精心挑選各種不同的咖啡產品，希望使用者能在這裡找到屬於自己獨特的咖啡饗宴。

我負責該專題的互動式頁面：咖啡地圖、咖啡占卜，以及會員收藏的功能。

主要框架使用React、Next.js作為前端，Node.js、Express.js為後端，以SCSS、Bootstrap撰寫視覺畫面，利用MySQL作為資料庫，用GitHub作為版本控制的工具。

![image](https://github.com/RockyJade/COFFSEEKER/assets/50537438/7b74668a-8a83-410a-8a9c-07343e8e52cd)

## 我負責的部分

- 頁面RWD切版：咖啡占卜、咖啡地圖、我的收藏頁面
- React程式開發：咖啡占卜、咖啡地圖、我的收藏：商品／課程
- Node.js資料庫串接：會員、收藏、商品、課程資料、Cafe Nomad API
- RESTful API 路由設計：占卜推薦商品、新增／刪除收藏商品、課程
- Figma 視覺規劃：咖啡占卜、咖啡地圖
- 建立MySQL資料庫：收藏商品、收藏課程

## 檔案導向

### 咖啡地圖

- [coffseeker-frontend/pages/map](https://github.com/RockyJade/COFFSEEKER/tree/5e4601c2e5be8afe6da9bd4708323086f51d12e7/coffseeker-frontend/pages/map)
- [coffseeker-frontend/components/map](https://github.com/RockyJade/COFFSEEKER/tree/5e4601c2e5be8afe6da9bd4708323086f51d12e7/coffseeker-frontend/components/map)
- [coffseeker-frontend/pages/api/fetchCafeData.js](https://github.com/RockyJade/COFFSEEKER/blob/main/coffseeker-frontend/pages/api/fetchCafeData.js)
- [coffseeker-frontend/styles/_map.scss](https://github.com/RockyJade/COFFSEEKER/blob/5e4601c2e5be8afe6da9bd4708323086f51d12e7/coffseeker-frontend/styles/_map.scss)

### 咖啡占卜
- [coffseeker-frontend/pages/infomation/divination](https://github.com/RockyJade/COFFSEEKER/tree/5e4601c2e5be8afe6da9bd4708323086f51d12e7/coffseeker-frontend/pages/infomation/divination)
- [coffseeker-frontend/components/divination](https://github.com/RockyJade/COFFSEEKER/tree/5e4601c2e5be8afe6da9bd4708323086f51d12e7/coffseeker-frontend/components/divination)
- [coffseeker-frontend/styles/_divination.scss](https://github.com/RockyJade/COFFSEEKER/blob/5e4601c2e5be8afe6da9bd4708323086f51d12e7/coffseeker-frontend/styles/_divination.scss)

### 收藏功能

#### 前端：
- [coffseeker-frontend/components/FavIcon.js](https://github.com/RockyJade/COFFSEEKER/blob/5e4601c2e5be8afe6da9bd4708323086f51d12e7/coffseeker-frontend/components/FavIcon.js)
- [coffseeker-frontend/components/FavIconC.js](https://github.com/RockyJade/COFFSEEKER/blob/5e4601c2e5be8afe6da9bd4708323086f51d12e7/coffseeker-frontend/components/FavIconC.js)
- [coffseeker-frontend/components/member/Favorite](https://github.com/RockyJade/COFFSEEKER/tree/5e4601c2e5be8afe6da9bd4708323086f51d12e7/coffseeker-frontend/components/member/Favorite)
- [coffseeker-frontend/components/fav](https://github.com/RockyJade/COFFSEEKER/tree/5e4601c2e5be8afe6da9bd4708323086f51d12e7/coffseeker-frontend/components/fav)
- [coffseeker-frontend/context/fav.js](https://github.com/RockyJade/COFFSEEKER/blob/5e4601c2e5be8afe6da9bd4708323086f51d12e7/coffseeker-frontend/context/fav.js)

#### 後端：
- [coffseeker-backend/routes/favorite.js](https://github.com/RockyJade/COFFSEEKER/blob/5e4601c2e5be8afe6da9bd4708323086f51d12e7/coffseeker-backend/routes/favorite.js)
