## 优先级

按照下列优先级进行翻译：

状态|URL|占比
---|---|----
[x]  | common/http/HttpClient  | 2.26
[x]  | common/NgForOf  | 1.95
[x]  | forms/NgModel  | 1.75
[x]  | core/Component  | 1.73
[x]  | common/NgIf  | 1.53
[x]  | core/NgModule  | 1.27
[x]  | router/Router  | 1.26
[ ]  | animations/animate  | 1.19
[x]  | common/NgClass  | 1.15
[x]  | common/DatePipe  | 1.11
[x]  | forms/FormsModule  | 1.05
[x]  | core/Input  | 1.04
[x]  | core/EventEmitter  | 0.99
[x]  | core/Injectable  | 0.99
[x]  | forms/FormGroup  | 0.96
[x]  | forms/FormControl  | 0.94
[x]  | router/ActivatedRoute  | 0.93
[x]  | forms/AbstractControl  | 0.91
[x]  | router/RouterLink  | 0.91
[x]  | core/ViewChild  | 0.89
[x]  | core/Directive  | 0.86
[x]  | router/Routes  | 0.72
[x]  | router/RouterModule  | 0.69
[x]  | router/Route  | 0.69
[x]  | common/http/HttpClientModule  | 0.67
[x]  | core/ElementRef  | 0.67
[x]  | core/OnInit  | 0.66
[x]  | common/UpperCasePipe  | 0.65
[ ]  | common/NgStyle  | 0.60
[ ]  | router/RouterOutlet  | 0.59
[ ]  | forms/Validators  | 0.59
[ ]  | common/http/HttpHeaders  | 0.56
[x]  | core/Pipe  | 0.52
[ ]  | common/NgSwitch  | 0.52
[ ]  | forms/NgForm  | 0.50
[ ]  | core/Renderer2  | 0.49
[x]  | core/HostListener  | 0.47
[ ]  | common/AsyncPipe  | 0.45
[ ]  | core/ViewContainerRef  | 0.42
[ ]  | common/NgTemplateOutlet  | 0.42
[ ]  | common/Location  | 0.41
[ ]  | platform-browser/BrowserModule  | 0.40
[ ]  | common/DecimalPipe  | 0.40
[ ]  | common/CurrencyPipe  | 0.39
[ ]  | router/RouterLinkActive  | 0.38
[ ]  | core/TemplateRef  | 0.38
[ ]  | forms/FormBuilder  | 0.37
[ ]  | common/http/HttpParams  | 0.35
[ ]  | core/OnChanges  | 0.35
[ ]  | forms/FormControlName  | 0.34
[x]  | core/Output  | 0.33
[ ]  | common/http/HttpInterceptor  | 0.30
[ ]  | common/http/HttpRequest  | 0.29
[ ]  | router/CanActivate  | 0.27
[ ]  | router  | 0.26
[ ]  | animations/style  | 0.25
[ ]  | common/SlicePipe  | 0.25
[ ]  | router/Event  | 0.25
[ ]  | common/JsonPipe  | 0.25
[x]  | forms/FormArray  | 0.25
[ ]  | common/CommonModule  | 0.24
[ ]  | router/NavigationExtras  | 0.24
[x]  | core/HostBinding  | 0.23
[x]  | core/ContentChild  | 0.22
[x]  | core/ViewChildren  | 0.22
[x]  | common/http/HttpResponse  | 0.22
[x]  | router/ActivatedRouteSnapshot  | 0.22
[ ]  | common/http  | 0.21
[ ]  | core/ChangeDetectorRef  | 0.21
[ ]  | router/NavigationStart  | 0.21
[ ]  | common/formatDate  | 0.21
[ ]  | core/ComponentFactoryResolver  | 0.20
[ ]  | forms/Form  | 0.20
[ ]  | common/http/HttpErrorResponse  | 0.20
[ ]  | core/QueryList  | 0.19
[ ]  | forms  | 0.19
[ ]  | animations/state  | 0.19
[ ]  | common  | 0.19
[ ]  | router/LoadChildren  | 0.18
[ ]  | router/ParamMap  | 0.18
[ ]  | animations/trigger  | 0.18
[ ]  | router/RouterLinkWithHref  | 0.18
[ ]  | core/AfterViewInit  | 0.18
[ ]  | forms/ReactiveFormsModule  | 0.18
[ ]  | common/http/HTTP_INTERCEPTORS  | 0.18
[ ]  | platform-browser/DomSanitizer  | 0.18
[ ]  | core/PipeTransform  | 0.18
[ ]  | core/SimpleChange  | 0.18
[ ]  | core/SimpleChanges  | 0.18
[ ]  | forms/NgSelectOption  | 0.17
[ ]  | common/PercentPipe  | 0.17
[ ]  | forms/ValidatorFn  | 0.17
[ ]  | http/RequestOptionsArgs  | 0.17
[ ]  | animations/animation  | 0.17
[ ]  | common/NgSwitchCase  | 0.16
[ ]  | core/testing/async  | 0.16

## 翻译方式

找到源码，并且把对应的 tsdoc 内容翻译了。

中文放在英文之后，并且要隔一个空行。

## 翻译内容

优先翻译函数主形态（如在 `common/http/src/client.ts` 中它通常都是重载形式中的最后一个），可以先不翻译各个重载形态。