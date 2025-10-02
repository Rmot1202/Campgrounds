# Android Lab 5 - *Campground Explorer Pt. 2: Offline Mode*

Submitted by: **Raven Mott**

**Campground Explorer** displays recent US National Park Service campgrounds and now supports **offline mode** by caching the most recent campground data locally using Room (SQLite). Users can still browse campground information even when offline or in Airplane mode.

Time spent: **6** hours spent in total

---

## Required Features

The following **required** functionality is completed:

- [X] **Campgrounds are displayed using a RecyclerView**
- [X] **User can navigate to a Campground Details screen**
- [X] **Campground images are downloaded and displayed using Glide**
- [X] **Most recently fetched campgrounds are cached locally in a Room database**
- [X] **If offline (Airplane mode) and the app is relaunched, cached campgrounds are loaded from the database**
- [X] **Database operations run asynchronously with Kotlin coroutines (Dispatchers.IO)**
- [X] **Single Source of Truth principle applied — UI always reads from the database, not directly from the API**

---

## Additional Features


---

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='yell.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

<!-- Replace this with whatever GIF tool you used! -->
GIF created with ...  
[Kap](https://getkap.co/) for macOS

---

## Notes

- Implemented **Room database** with Entity, DAO, and Database class  
- Used **coroutines** with `Dispatchers.IO` to handle database operations asynchronously  
- Followed **Single Source of Truth (SSOT)** principle — UI always displays data from the database  
- Practiced integrating **local caching with remote API calls**  

---

## License

```

Copyright (2025) Raven Mott

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

```
http://www.apache.org/licenses/LICENSE-2.0
```

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

```
```

