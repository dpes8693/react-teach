# 從零開始學 React

## 目錄

### 1 摸索(讓眼睛習慣新的框架程式放哪邊)

1-1 看一下舊版的樣子，W3school 範例

1-2 看一下用 class 的版本，看不懂很正常，我用之後會用 Function 版本的寫法~叫做 Hook

1-3 Hello World 第一次執行 React

### 2 理解名詞(才能看懂文件)

2-1

- babel
- JSX {function(參數)}
- 語法
  - ReactDOM.createRoot(root)
  - root.render
- Self-Closing
- SPA

2-2

- JSX
  - 三元運算子
  - 用陣列傳多個 tag
  - 用 map 將文字陣列渲染成`<li>`

更新 UI 唯一的方式是建立一個新的 element，並且將它傳入到 root.render

2-3 了解屬於 React 的語法(才能看懂別人的範例)

- Functional Component
  - 首字大寫(function 和 tag 都是)
  - return JSX 習慣用(小括號包起來)
  - 參數傳遞 porps

### 3 學目前最流行的 Hook (基本功)

3-1

- 利用表單範例加深 props 觀念: 父傳子

3-2

- 接續 3-1 觀念 子傳父
- 懶人包 父宣告一個方法用props傳給子，子宣告接收該方法並在觸發事件時回傳(參數)

其他 React 範例

- useEffect
- useContext(部分是 React16)

===

## 推薦文章

[React Class-based vs Functional Component](https://linyencheng.github.io/2020/02/02/react-component-class-based-vs-functional/)

===

```md
# 重點整理

## React Hook

- useState | 操作 data，單向資料流 | getter setter
- useEffect | 在 render 渲染结束后执行 | 監聽

---

- useContext | 在不同 component 之間傳遞資料，部分取代 Redux 功能 | props
- useMemo | 在需要的 data 的時候執行 | 遇到複雜耗時計算時使用

---

- useRef | 不會主動觸發頁面重新渲染 | 打後端 API

## 使用 Bootstrap

https://ithelp.ithome.com.tw/articles/10239905

## 大概知道有生命週期 Life Cycle
```
