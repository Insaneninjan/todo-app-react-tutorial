# Todo list with React

## Terms
hooks
component
hot reload

```
% create-react-app [app名]
```

## hooks
- useState()
  const [状態変数, 状態を変更するための関数] = useState(状態の初期値);
  const [stateValue, set-stateValue()] = useState
  (intialState)

- useRef()
  Classコンポーネント時のref属性の代わりに、useRefを使って要素への参照を行う。またuseRefでは、useStateのようにコンポーネント内での値を保持することが可能
  const refObject = useRef(initialValue)

useStateを利用している場合はstateの変更される度にコンポーネントの再レンダリングが発生しますが、useRefは値が変更になっても、コンポーネントの再レンダリングは発生しない

コンポーネントの再レンダリングはしたくないけど、内部に保持している値だけを更新したい場合は、保持したい値をuseStateではなく、useRefを利用するのが良さそうです。


## Syntax
- spread 構文
const hoge = [...variables, value2];


# Library
- uuid
  ユニークなUUIDを作成
