# File tự động tạo ra.
- node_modules: khi gõ -> npm install
- package-lock.json: sau khi install

# Cài thư viện vào dự án.
- npm i <ten_thu_vien>

# src: Nơi code chính
# public: Nơi lưu trữ những file static
- icons
- images
- audios
- font-family


# cli: Chuyển đổi code từ scss -> css
- npx sass <dir_input> <dir_output>

- npx sass src/**/*.scss dist/index.css --watch
- --watch: develop

# Tính năng của scss.
- nesting
- extend kế thừa được code css
- khai báo biến
- import và export: @use, @forward
    - @import: cũ.
- @mixin, @function

- BEM: Block Element Modifier
    - Block-Element
    - Element-Modifier
    - Block-Modifier
    - Block-Element-Modifier: Cải thiện.

<div class='nav d-flex bgc-primary p-2 mt-2 d-flex'>
    <p class='nav-item fz-sm clr-success d-flex'>lorem5</p>
    <button class='block-element-button block-element-button__success'>Click</button>
</div>