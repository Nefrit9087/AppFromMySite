import UIKit
import WebKit

class ViewController: UIViewController, WKNavigationDelegate {
    
    var webView: WKWebView!

    override func viewDidLoad() {
        super.viewDidLoad()
        
        // Создание экземпляра WKWebView
        webView = WKWebView(frame: view.bounds)
        webView.navigationDelegate = self
        
        // Добавление WKWebView в иерархию представлений
        view.addSubview(webView)
        
        // Загрузка вашего сайта
        if let url = URL(string: "https://platonrun.ru") {
            let request = URLRequest(url: url)
            webView.load(request)
        }
    }
}
