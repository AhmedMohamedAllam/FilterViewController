# FilterViewController
Filter any array of data with UITextField as searchTextField

# How to use

- inherit `FilterViewController<#model_type#>`

- override searchTextField and connnect it to your storyboard

    `@IBOutlet override weak var searchTextField: UITextField!{
        get{return super.searchTextField}
        set{super.searchTextField = newValue}
    }`

- override `reloadData()`
- override `filterLogic(searchText:)`
