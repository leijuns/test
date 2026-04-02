# Polaris Icons 变化对比：v9 → v13

本文档对比了 Shopify Polaris v9（`@shopify/polaris@9.9.0`，对应 `@shopify/polaris-icons@4.22.0`）和 Polaris v13（`@shopify/polaris@13.9.5`，对应 `@shopify/polaris-icons@9.3.1`）之间图标（icons）的差异。

## 版本变化概览

| 维度 | 数值 |
| --- | --- |
| Polaris v9 图标总数 | 410 |
| Polaris v13 图标总数 | 534 |
| 重命名图标（去重后的新名称数） | 335 |
| 新增图标（v13 独有） | 199 |
| 删除图标（v9 存在但 v13 无对应） | 0 |

## 关键变化说明

### 命名规范变化

Polaris Icons v8.0.0（在 `@shopify/polaris` v10+ 之后引入）进行了一次**重大重命名**：

- 移除了 `Major` / `Minor` 后缀区分，统一使用 `Icon` 后缀
- 例如：`AbandonedCartMajor` + `AbandonedCartMinor` → `CartAbandonedIcon`
- 部分图标进行了语义重命名（如 `AccessibilityMajor` → `EyeCheckMarkIcon`）
- 可通过官方迁移工具自动更新：`npx @shopify/polaris-migrator icons-v8-update-names <path>`

### 各大版本 Icons 变化摘要

| 版本 | Icons 包版本 | 变化 |
| --- | --- | --- |
| @shopify/polaris v9 | polaris-icons v4.22.0 | 基准版本，使用 Major/Minor 命名 |
| @shopify/polaris v10 | polaris-icons v8.0.0 | **重大重命名**：移除 Major/Minor，统一 Icon 后缀；新增 BillIcon 等多个图标 |
| @shopify/polaris v11 | polaris-icons v8.x | 新增 IncentiveIcon, DatabaseConnectIcon, 列表图标等 |
| @shopify/polaris v12 | polaris-icons v8.x-9.x | 新增 PersonSegmentIcon, ArrowDiagonalIcon, SunIcon, MoonIcon, BulletIcon 等；图标设计更新 |
| @shopify/polaris v13 | polaris-icons v9.3.1 | 新增 CatalogIcon, ProductUnavailableIcon, OrganizationFilledIcon, Finance icons 等 |

---

## 一、重命名图标对照表

以下图标从 v9 的 Major/Minor 命名重命名为 v13 的统一 Icon 命名。

| v9 旧名称 | v13 新名称 |
| --- | --- |
| `AdjustMinor` | `AdjustIcon` |
| `AffiliateMajor` | `AffiliateIcon` |
| `TransportMajor` | `AirplaneIcon` |
| `DisputeMinor` | `AlertBubbleIcon` |
| `AlertMinor`, `CircleAlertMajor` | `AlertCircleIcon` |
| `DiamondAlertMajor` | `AlertDiamondIcon` |
| `RiskMajor`, `RiskMinor` | `AlertTriangleIcon` |
| `AppExtensionMinor` | `AppExtensionIcon` |
| `AppsMajor`, `AppsMinor` | `AppsIcon` |
| `ArchiveMajor`, `ArchiveMinor` | `ArchiveIcon` |
| `ArrowDownMinor` | `ArrowDownIcon` |
| `ArrowLeftMinor`, `MobileBackArrowMajor` | `ArrowLeftIcon` |
| `ArrowRightMinor` | `ArrowRightIcon` |
| `ArrowUpMinor` | `ArrowUpIcon` |
| `AttachmentMajor` | `AttachmentIcon` |
| `AutomationMajor` | `AutomationIcon` |
| `BackspaceMajor` | `BackspaceIcon` |
| `BankMajor`, `FinancesMinor` | `BankIcon` |
| `BarcodeMajor` | `BarcodeIcon` |
| `BlogMajor` | `BlogIcon` |
| `ReadTimeMinor` | `BookIcon` |
| `VocabularyMajor` | `BookOpenIcon` |
| `BugMajor` | `BugIcon` |
| `ButtonMinor` | `ButtonIcon` |
| `BuyButtonMajor` | `ButtonPressIcon` |
| `MonerisMajor` | `CalculatorIcon` |
| `CalendarTickMajor` | `CalendarCheckIcon` |
| `CalendarMajor`, `CalendarMinor` | `CalendarIcon` |
| `FlipCameraMajor` | `CameraFlipIcon` |
| `CameraMajor` | `CameraIcon` |
| `CaretDownMinor`, `DropdownMinor` | `CaretDownIcon` |
| `CaretUpMinor` | `CaretUpIcon` |
| `AbandonedCartMajor` | `CartAbandonedIcon` |
| `DiscountAutomaticMajor` | `CartDiscountIcon` |
| `CartDownMajor` | `CartDownIcon` |
| `CartMajor`, `CheckoutMajor` | `CartIcon` |
| `QuickSaleMajor` | `CartSaleIcon` |
| `CartUpMajor` | `CartUpIcon` |
| `CashDollarMajor` | `CashDollarIcon` |
| `CashEuroMajor` | `CashEuroIcon` |
| `CashPoundMajor` | `CashPoundIcon` |
| `CashRupeeMajor` | `CashRupeeIcon` |
| `CashYenMajor` | `CashYenIcon` |
| `CategoriesMajor` | `CategoriesIcon` |
| `ChannelsMajor` | `ChannelsIcon` |
| `PopularMajor` | `ChartPopularIcon` |
| `AnalyticsMajor`, `AnalyticsMinor` | `ChartVerticalIcon` |
| `ChatMajor`, `ConversationMinor` | `ChatIcon` |
| `ReferralMajor` | `ChatReferralIcon` |
| `CircleTickMajor`, `CircleTickMinor`, `CircleTickOutlineMinor` | `CheckCircleIcon` |
| `MobileAcceptMajor`, `TickMinor` | `CheckIcon` |
| `TickSmallMinor` | `CheckSmallIcon` |
| `EnableSelectionMinor` | `CheckboxIcon` |
| `ChevronDownMinor` | `ChevronDownIcon` |
| `ChevronLeftMinor`, `MobileChevronMajor` | `ChevronLeftIcon` |
| `ChevronRightMinor` | `ChevronRightIcon` |
| `ChevronUpMinor` | `ChevronUpIcon` |
| `CircleChevronDownMinor` | `CircleChevronDownIcon` |
| `CircleChevronLeftMinor` | `CircleChevronLeftIcon` |
| `CircleChevronRightMinor` | `CircleChevronRightIcon` |
| `CircleChevronUpMinor` | `CircleChevronUpIcon` |
| `CircleDownMajor` | `CircleDownIcon` |
| `CircleLeftMajor` | `CircleLeftIcon` |
| `CircleRightMajor` | `CircleRightIcon` |
| `CircleUpMajor` | `CircleUpIcon` |
| `ChecklistMajor` | `ClipboardCheckIcon` |
| `ChecklistAlternateMajor` | `ClipboardChecklistIcon` |
| `ClipboardMinor` | `ClipboardIcon` |
| `ClockMajor`, `ClockMinor` | `ClockIcon` |
| `AddCodeMajor` | `CodeAddIcon` |
| `CodeMajor`, `EmbedMinor` | `CodeIcon` |
| `FeaturedCollectionMajor` | `CollectionFeaturedIcon` |
| `CollectionsMajor` | `CollectionIcon` |
| `ColorsMajor` | `ColorIcon` |
| `ColorNoneMinor` | `ColorNoneIcon` |
| `NavigationMajor` | `CompassIcon` |
| `ComposeMajor` | `ComposeIcon` |
| `ConfettiMajor` | `ConfettiIcon` |
| `ConnectMinor` | `ConnectIcon` |
| `LegalMajor` | `ContractIcon` |
| `ButtonCornerPillMajor` | `CornerPillIcon` |
| `ButtonCornerRoundedMajor` | `CornerRoundIcon` |
| `ButtonCornerSquareMajor` | `CornerSquareIcon` |
| `CreditCardCancelMajor` | `CreditCardCancelIcon` |
| `CreditCardMajor` | `CreditCardIcon` |
| `CreditCardPercentMajor` | `CreditCardPercentIcon` |
| `CardReaderChipMajor` | `CreditCardReaderChipIcon` |
| `CardReaderMajor` | `CreditCardReaderIcon` |
| `CardReaderTapMajor` | `CreditCardReaderTapIcon` |
| `CreditCardSecureMajor` | `CreditCardSecureIcon` |
| `TapChipMajor` | `CreditCardTapChipIcon` |
| `CurrencyConvertMinor` | `CurrencyConvertIcon` |
| `BehaviorMajor` | `CursorIcon` |
| `DataVisualizationMajor` | `DataPresentationIcon` |
| `DeleteMajor`, `DeleteMinor` | `DeleteIcon` |
| `ShipmentMajor` | `DeliveryIcon` |
| `DesktopMajor` | `DesktopIcon` |
| `CircleDisableMinor`, `CircleDisabledMajor` | `DisabledIcon` |
| `DiscountCodeMajor` | `DiscountCodeIcon` |
| `DiscountsMajor`, `DiscountsMinor` | `DiscountIcon` |
| `DnsSettingsMajor` | `DnsSettingsIcon` |
| `DomainsMajor` | `DomainIcon` |
| `LandingPageMajor` | `DomainLandingPageIcon` |
| `DomainNewMajor` | `DomainNewIcon` |
| `DomainRedirectMinor` | `DomainRedirectIcon` |
| `DragDropMajor` | `DragDropIcon` |
| `DragHandleMinor` | `DragHandleIcon` |
| `DuplicateMinor` | `DuplicateIcon` |
| `EditMajor`, `EditMinor` | `EditIcon` |
| `FollowUpEmailMajor` | `EmailFollowUpIcon` |
| `EmailMajor`, `InviteMinor` | `EmailIcon` |
| `EmailNewsletterMajor` | `EmailNewsletterIcon` |
| `EnvelopeMajor` | `EnvelopeIcon` |
| `SoftPackMajor` | `EnvelopeSoftPackIcon` |
| `ExchangeMajor` | `ExchangeIcon` |
| `ExitMajor`, `LogOutMinor` | `ExitIcon` |
| `ExportMinor` | `ExportIcon` |
| `ExternalMinor` | `ExternalIcon` |
| `ExternalSmallMinor` | `ExternalSmallIcon` |
| `AccessibilityMajor` | `EyeCheckMarkIcon` |
| `FirstVisitMajor` | `EyeFirstIcon` |
| `ResourcesMajor` | `EyeglassesIcon` |
| `FaviconMajor` | `FaviconIcon` |
| `FilterMajor` | `FilterIcon` |
| `FlagMajor` | `FlagIcon` |
| `CapitalMajor` | `FlowerIcon` |
| `FolderPlusMajor` | `FolderAddIcon` |
| `FolderDownMajor` | `FolderDownIcon` |
| `FolderMajor` | `FolderIcon` |
| `FolderMinusMajor` | `FolderRemoveIcon` |
| `FolderUpMajor` | `FolderUpIcon` |
| `FoodMajor` | `FoodIcon` |
| `WholesaleMajor` | `ForkliftIcon` |
| `FormsMajor` | `FormsIcon` |
| `GamesConsoleMajor` | `GamesIcon` |
| `GiftCardMajor`, `GiftCardMinor` | `GiftCardIcon` |
| `GlobeMajor`, `GlobeMinor` | `GlobeIcon` |
| `HashtagMajor` | `HashtagIcon` |
| `HeartMajor` | `HeartIcon` |
| `HideMinor` | `HideIcon` |
| `HomeMajor`, `HomeMinor` | `HomeIcon` |
| `IconsMajor` | `IconsIcon` |
| `AddImageMajor` | `ImageAddIcon` |
| `ImageAltMajor`, `ImageAltMinor` | `ImageAltIcon` |
| `ImageMajor` | `ImageIcon` |
| `ImageWithTextOverlayMajor` | `ImageWithTextOverlayIcon` |
| `ImagesMajor` | `ImagesIcon` |
| `ImportMinor`, `InstallMinor` | `ImportIcon` |
| `IncomingMajor` | `IncomingIcon` |
| `CircleInformationMajor`, `InfoMinor` | `InfoIcon` |
| `ExistingInventoryMajor`, `InventoryMajor` | `InventoryIcon` |
| `UpdateInventoryMajor` | `InventoryUpdatedIcon` |
| `IqMajor` | `IqIcon` |
| `KeyMajor` | `KeyIcon` |
| `HideKeyboardMajor` | `KeyboardHideIcon` |
| `LabelPrinterMajor` | `LabelPrinterIcon` |
| `LanguageMinor` | `LanguageIcon` |
| `BlockMinor` | `LayoutBlockIcon` |
| `BuyButtonHorizontalLayoutMajor` | `LayoutBuyButtonHorizontalIcon` |
| `BuyButtonButtonLayoutMajor` | `LayoutBuyButtonIcon` |
| `BuyButtonVerticalLayoutMajor` | `LayoutBuyButtonVerticalIcon` |
| `Column1Major` | `LayoutColumn1Icon` |
| `Columns2Major` | `LayoutColumns2Icon` |
| `Columns3Major`, `Columns3Minor` | `LayoutColumns3Icon` |
| `FooterMajor` | `LayoutFooterIcon` |
| `HeaderMajor` | `LayoutHeaderIcon` |
| `LogoBlockMajor` | `LayoutLogoBlockIcon` |
| `DetailedPopUpMajor` | `LayoutPopupIcon` |
| `SectionMajor` | `LayoutSectionIcon` |
| `SidebarLeftMajor` | `LayoutSidebarLeftIcon` |
| `SidebarRightMajor` | `LayoutSidebarRightIcon` |
| `HintMajor` | `LightbulbIcon` |
| `LinkMinor` | `LinkIcon` |
| `ListMajor` | `ListBulletedIcon` |
| `LiveViewMajor` | `LiveIcon` |
| `LocationMajor`, `LocationsMinor` | `LocationIcon` |
| `LockMajor`, `LockMinor` | `LockIcon` |
| `MarketsMajor` | `MarketsIcon` |
| `MaximizeMajor`, `MaximizeMinor` | `MaximizeIcon` |
| `DigitalMediaReceiverMajor` | `MediaReceiverIcon` |
| `PromoteMinor` | `MegaphoneIcon` |
| `MentionMajor` | `MentionIcon` |
| `CircleDotsMajor`, `HorizontalDotsMinor`, `MobileHorizontalDotsMajor` | `MenuHorizontalIcon` |
| `MobileHamburgerMajor` | `MenuIcon` |
| `MobileVerticalDotsMajor` | `MenuVerticalIcon` |
| `MergeMinor` | `MergeIcon` |
| `MicrophoneMajor` | `MicrophoneIcon` |
| `MinimizeMajor`, `MinimizeMinor` | `MinimizeIcon` |
| `CircleMinusMajor`, `CircleMinusMinor`, `CircleMinusOutlineMinor` | `MinusCircleIcon` |
| `MinusMinor` | `MinusIcon` |
| `MobileMajor` | `MobileIcon` |
| `FinancesMajor` | `MoneyIcon` |
| `NatureMajor` | `NatureIcon` |
| `AddNoteMajor` | `NoteAddIcon` |
| `NoteMajor`, `NoteMinor` | `NoteIcon` |
| `NotificationMajor` | `NotificationIcon` |
| `DraftOrdersMajor` | `OrderDraftIcon` |
| `FirstOrderMajor` | `OrderFirstIcon` |
| `MarkFulfilledMinor` | `OrderFulfilledIcon` |
| `OrdersMajor`, `OrdersMinor` | `OrderIcon` |
| `RepeatOrderMajor` | `OrderRepeatIcon` |
| `UnfulfilledMajor` | `OrderUnfulfilledIcon` |
| `OrderStatusMinor` | `OrdersStatusIcon` |
| `OutgoingMajor` | `OutgoingIcon` |
| `PackageMajor` | `PackageIcon` |
| `PagePlusMajor` | `PageAddIcon` |
| `TimelineAttachmentMajor` | `PageAttachmentIcon` |
| `PageDownMajor` | `PageDownIcon` |
| `FeaturedContentMajor` | `PageHeartIcon` |
| `PageMajor` | `PageIcon` |
| `PageMinusMajor` | `PageRemoveIcon` |
| `PageUpMajor` | `PageUpIcon` |
| `PaginationEndMinor` | `PaginationEndIcon` |
| `PaginationStartMinor` | `PaginationStartIcon` |
| `PaintBrushMajor` | `PaintBrushFlatIcon` |
| `IllustrationMajor` | `PaintBrushRoundIcon` |
| `PauseCircleMajor`, `PauseMajor`, `PauseMinor` | `PauseCircleIcon` |
| `CapturePaymentMinor` | `PaymentCaptureIcon` |
| `PaymentsMajor` | `PaymentIcon` |
| `CustomerPlusMajor` | `PersonAddIcon` |
| `CustomersMajor`, `CustomersMinor` | `PersonIcon` |
| `CustomerMinusMajor` | `PersonRemoveIcon` |
| `PhoneMajor` | `PhoneIcon` |
| `PhoneInMajor` | `PhoneInIcon` |
| `PhoneOutMajor` | `PhoneOutIcon` |
| `PinMajor`, `PinMinor` | `PinFilledIcon` |
| `PlayCircleMajor` | `PlayCircleIcon` |
| `PlayMajor`, `PlayMinor` | `PlayIcon` |
| `CirclePlusMajor`, `CirclePlusMinor`, `CirclePlusOutlineMinor` | `PlusCircleIcon` |
| `AddMajor`, `MobilePlusMajor`, `PlusMinor` | `PlusIcon` |
| `PointOfSaleMajor` | `PointOfSaleIcon` |
| `PrintMajor`, `PrintMinor` | `PrintIcon` |
| `AddProductMajor` | `ProductAddIcon` |
| `ProductsMajor`, `ProductsMinor` | `ProductIcon` |
| `RemoveProductMajor` | `ProductRemoveIcon` |
| `ProductReturnsMinor` | `ProductReturnIcon` |
| `ProfileMajor`, `ProfileMinor` | `ProfileIcon` |
| `QuestionMarkInverseMajor`, `QuestionMarkInverseMinor`, `QuestionMarkMajor`, `QuestionMarkMinor` | `QuestionCircleIcon` |
| `BillingStatementDollarMajor` | `ReceiptDollarIcon` |
| `BillingStatementEuroMajor` | `ReceiptEuroIcon` |
| `ReceiptMajor` | `ReceiptIcon` |
| `MarkPaidMinor` | `ReceiptPaidIcon` |
| `BillingStatementPoundMajor` | `ReceiptPoundIcon` |
| `RefundMajor`, `RefundMinor` | `ReceiptRefundIcon` |
| `BillingStatementRupeeMajor` | `ReceiptRupeeIcon` |
| `BillingStatementYenMajor` | `ReceiptYenIcon` |
| `RedoMajor` | `RedoIcon` |
| `ReferralCodeMajor` | `ReferralCodeIcon` |
| `RefreshMajor`, `RefreshMinor` | `RefreshIcon` |
| `ReplaceMajor` | `ReplaceIcon` |
| `ReplayMinor` | `ReplayIcon` |
| `ResetMinor` | `ResetIcon` |
| `ReturnMinor` | `ReturnIcon` |
| `SandboxMajor` | `SandboxIcon` |
| `SaveMinor` | `SaveIcon` |
| `SearchMajor`, `SearchMinor` | `SearchIcon` |
| `PriceLookupMinor` | `SearchListIcon` |
| `RecentSearchesMajor` | `SearchRecentIcon` |
| `ReportMinor`, `ReportsMajor` | `SearchResourceIcon` |
| `SelectMinor` | `SelectIcon` |
| `SendMajor` | `SendIcon` |
| `SettingsMajor`, `SettingsMinor` | `SettingsIcon` |
| `ShareIosMinor`, `ShareMinor` | `ShareIcon` |
| `SecureMajor` | `ShieldCheckMarkIcon` |
| `FraudProtectUnprotectedMajor`, `FraudProtectUnprotectedMinor` | `ShieldNoneIcon` |
| `FraudProtectPendingMajor`, `FraudProtectPendingMinor` | `ShieldPendingIcon` |
| `FraudProtectMajor`, `FraudProtectMinor` | `ShieldPersonIcon` |
| `ShopcodesMajor` | `ShopcodesIcon` |
| `SlideshowMajor` | `SlideshowIcon` |
| `SmileyHappyMajor` | `SmileyHappyIcon` |
| `SmileyJoyMajor` | `SmileyJoyIcon` |
| `SmileyNeutralMajor` | `SmileyNeutralIcon` |
| `SmileySadMajor` | `SmileySadIcon` |
| `SocialAdMajor` | `SocialAdIcon` |
| `SocialPostMajor` | `SocialPostIcon` |
| `SortAscendingMajor` | `SortAscendingIcon` |
| `SortDescendingMajor` | `SortDescendingIcon` |
| `SortMinor` | `SortIcon` |
| `SoundMajor` | `SoundIcon` |
| `ActivitiesMajor` | `SportsIcon` |
| `StarFilledMinor` | `StarFilledIcon` |
| `FavoriteMajor`, `StarOutlineMinor` | `StarIcon` |
| `StoreStatusMajor` | `StatusIcon` |
| `StoreMajor`, `StoreMinor` | `StoreIcon` |
| `ImportStoreMajor` | `StoreImportIcon` |
| `ManagedStoreMajor` | `StoreManagedIcon` |
| `OnlineStoreMajor`, `OnlineStoreMinor` | `StoreOnlineIcon` |
| `TabletMajor` | `TabletIcon` |
| `MarketingMajor`, `MarketingMinor` | `TargetIcon` |
| `TaxMajor` | `TaxIcon` |
| `TeamMajor` | `TeamIcon` |
| `TextAlignmentCenterMajor` | `TextAlignCenterIcon` |
| `TextAlignmentLeftMajor` | `TextAlignLeftIcon` |
| `TextAlignmentRightMajor` | `TextAlignRightIcon` |
| `TextBlockMajor` | `TextBlockIcon` |
| `TypeMajor` | `TextFontIcon` |
| `GrammarMajor` | `TextGrammarIcon` |
| `TextMajor` | `TextIcon` |
| `ColumnWithTextMajor` | `TextInColumnsIcon` |
| `BlockquoteMajor` | `TextQuoteIcon` |
| `TitleMinor` | `TextTitleIcon` |
| `ImageWithTextMajor` | `TextWithImageIcon` |
| `ThemeEditMajor` | `ThemeEditIcon` |
| `ThemesMajor` | `ThemeIcon` |
| `ThemeStoreMajor` | `ThemeStoreIcon` |
| `TemplateMajor` | `ThemeTemplateIcon` |
| `ThumbsDownMajor`, `ThumbsDownMinor` | `ThumbsDownIcon` |
| `ThumbsUpMajor`, `ThumbsUpMinor` | `ThumbsUpIcon` |
| `TipsMajor` | `TipJarIcon` |
| `TransactionFeeDollarMajor` | `TransactionFeeDollarIcon` |
| `TransactionFeeEuroMajor` | `TransactionFeeEuroIcon` |
| `TransactionFeePoundMajor` | `TransactionFeePoundIcon` |
| `TransactionFeeRupeeMajor` | `TransactionFeeRupeeIcon` |
| `TransactionFeeYenMajor` | `TransactionFeeYenIcon` |
| `TransactionMajor` | `TransactionIcon` |
| `TransferMajor` | `TransferIcon` |
| `TransferInMajor` | `TransferInIcon` |
| `TransferWithinShopifyMajor` | `TransferInternalIcon` |
| `TransferOutMajor` | `TransferOutIcon` |
| `UndoMajor` | `UndoIcon` |
| `UnknownDeviceMajor` | `UnknownDeviceIcon` |
| `UploadMajor` | `UploadIcon` |
| `VariantMajor` | `VariantIcon` |
| `ViewMajor`, `ViewMinor` | `ViewIcon` |
| `ViewportNarrowMajor` | `ViewportNarrowIcon` |
| `ViewportWideMajor` | `ViewportWideIcon` |
| `BalanceMajor` | `WalletIcon` |
| `WandMajor`, `WandMinor` | `WandIcon` |
| `WearableMajor` | `WatchIcon` |
| `WifiMajor` | `WifiIcon` |
| `JobsMajor` | `WorkIcon` |
| `ToolsMajor`, `TroubleshootMajor` | `WrenchIcon` |
| `CircleCancelMajor`, `CircleCancelMinor` | `XCircleIcon` |
| `MobileCancelMajor` | `XIcon` |
| `CancelSmallMinor` | `XSmallIcon` |

---

## 二、新增图标（仅在 v13 中存在）

以下 **199** 个图标是 v13 中新增的，在 v9 中不存在对应图标。

| 序号 | 图标名称 |
| --- | --- |
| 1 | `AppsFilledIcon` |
| 2 | `ArrowDiagonalIcon` |
| 3 | `ArrowsInHorizontalIcon` |
| 4 | `ArrowsOutHorizontalFilledIcon` |
| 5 | `ArrowsOutHorizontalIcon` |
| 6 | `AtmWithdrawalIcon` |
| 7 | `AttachmentFilledIcon` |
| 8 | `AutomationFilledIcon` |
| 9 | `BankFilledIcon` |
| 10 | `BillFilledIcon` |
| 11 | `BillIcon` |
| 12 | `BlankFilledIcon` |
| 13 | `BlankIcon` |
| 14 | `BulletIcon` |
| 15 | `CalendarTimeIcon` |
| 16 | `CartAbandonedFilledIcon` |
| 17 | `CartDownFilledIcon` |
| 18 | `CartFilledIcon` |
| 19 | `CashDollarFilledIcon` |
| 20 | `CatalogIcon` |
| 21 | `ChartCohortIcon` |
| 22 | `ChartDonutIcon` |
| 23 | `ChartFunnelIcon` |
| 24 | `ChartHistogramFirstIcon` |
| 25 | `ChartHistogramFirstLastIcon` |
| 26 | `ChartHistogramFlatIcon` |
| 27 | `ChartHistogramFullIcon` |
| 28 | `ChartHistogramGrowthIcon` |
| 29 | `ChartHistogramLastIcon` |
| 30 | `ChartHistogramSecondLastIcon` |
| 31 | `ChartHorizontalIcon` |
| 32 | `ChartLineIcon` |
| 33 | `ChartStackedIcon` |
| 34 | `ChartVerticalFilledIcon` |
| 35 | `ClipboardCheckFilledIcon` |
| 36 | `CollectionFilledIcon` |
| 37 | `CollectionListIcon` |
| 38 | `CollectionReferenceIcon` |
| 39 | `ContentFilledIcon` |
| 40 | `ContentIcon` |
| 41 | `ContractFilledIcon` |
| 42 | `CropIcon` |
| 43 | `CursorBannerIcon` |
| 44 | `CursorFilledIcon` |
| 45 | `CursorOptionIcon` |
| 46 | `DataTableIcon` |
| 47 | `DatabaseAddIcon` |
| 48 | `DatabaseConnectIcon` |
| 49 | `DatabaseIcon` |
| 50 | `DeliveryFilledIcon` |
| 51 | `DiscountFilledIcon` |
| 52 | `DockFloatingIcon` |
| 53 | `DockSideIcon` |
| 54 | `DomainFilledIcon` |
| 55 | `EnterIcon` |
| 56 | `EyeDropperIcon` |
| 57 | `FileFilledIcon` |
| 58 | `FileIcon` |
| 59 | `FinanceFilledIcon` |
| 60 | `FinanceIcon` |
| 61 | `FlipHorizontalIcon` |
| 62 | `FlipVerticalIcon` |
| 63 | `FlowerFilledIcon` |
| 64 | `GaugeIcon` |
| 65 | `GiftCardFilledIcon` |
| 66 | `GlobeAsiaFilledIcon` |
| 67 | `GlobeAsiaIcon` |
| 68 | `GlobeEUFilledIcon` |
| 69 | `GlobeEUIcon` |
| 70 | `GlobeFilledIcon` |
| 71 | `HashtagDecimalIcon` |
| 72 | `HomeFilledIcon` |
| 73 | `IconsFilledIcon` |
| 74 | `IdentityCardFilledIcon` |
| 75 | `IdentityCardIcon` |
| 76 | `ImageExploreIcon` |
| 77 | `ImageMagicIcon` |
| 78 | `InboundIcon` |
| 79 | `IncentiveIcon` |
| 80 | `InventoryFilledIcon` |
| 81 | `KeyboardIcon` |
| 82 | `LanguageFilledIcon` |
| 83 | `LanguageTranslateIcon` |
| 84 | `LayoutRows2Icon` |
| 85 | `ListBulletedFilledIcon` |
| 86 | `ListNumberedIcon` |
| 87 | `LiveFilledIcon` |
| 88 | `LocationFilledIcon` |
| 89 | `LocationNoneIcon` |
| 90 | `LockFilledIcon` |
| 91 | `LogoCriteoIcon` |
| 92 | `LogoFacebookIcon` |
| 93 | `LogoGoogleIcon` |
| 94 | `LogoInstagramIcon` |
| 95 | `LogoMetaIcon` |
| 96 | `LogoPinterestIcon` |
| 97 | `LogoSnapchatIcon` |
| 98 | `LogoTiktokIcon` |
| 99 | `LogoTumblrIcon` |
| 100 | `LogoTwitchIcon` |
| 101 | `LogoVimeoIcon` |
| 102 | `LogoXIcon` |
| 103 | `LogoYoutubeIcon` |
| 104 | `MagicIcon` |
| 105 | `MakePaymentIcon` |
| 106 | `MarketsEuroFilledIcon` |
| 107 | `MarketsEuroIcon` |
| 108 | `MarketsFilledIcon` |
| 109 | `MarketsRupeeFilledIcon` |
| 110 | `MarketsRupeeIcon` |
| 111 | `MarketsYenFilledIcon` |
| 112 | `MarketsYenIcon` |
| 113 | `MeasurementSizeIcon` |
| 114 | `MeasurementVolumeIcon` |
| 115 | `MeasurementWeightIcon` |
| 116 | `MegaphoneFilledIcon` |
| 117 | `MetafieldsFilledIcon` |
| 118 | `MetafieldsIcon` |
| 119 | `MetaobjectFilledIcon` |
| 120 | `MetaobjectIcon` |
| 121 | `MetaobjectListIcon` |
| 122 | `MetaobjectReferenceIcon` |
| 123 | `MoneyFilledIcon` |
| 124 | `MoneyNoneIcon` |
| 125 | `MoonIcon` |
| 126 | `NotificationFilledIcon` |
| 127 | `OrderDraftFilledIcon` |
| 128 | `OrderFilledIcon` |
| 129 | `OrganizationFilledIcon` |
| 130 | `OrganizationIcon` |
| 131 | `OutboundIcon` |
| 132 | `OutdentIcon` |
| 133 | `PackageFilledIcon` |
| 134 | `PackageFulfilledIcon` |
| 135 | `PackageOnHoldIcon` |
| 136 | `PackageReturnedIcon` |
| 137 | `PageClockFilledIcon` |
| 138 | `PageClockIcon` |
| 139 | `PageReferenceIcon` |
| 140 | `PaperCheckIcon` |
| 141 | `PasskeyFilledIcon` |
| 142 | `PasskeyIcon` |
| 143 | `PaymentFilledIcon` |
| 144 | `PayoutDollarIcon` |
| 145 | `PayoutEuroIcon` |
| 146 | `PayoutIcon` |
| 147 | `PayoutPoundIcon` |
| 148 | `PayoutRupeeIcon` |
| 149 | `PayoutYenIcon` |
| 150 | `PersonExitIcon` |
| 151 | `PersonFilledIcon` |
| 152 | `PersonLockFilledIcon` |
| 153 | `PersonLockIcon` |
| 154 | `PersonSegmentIcon` |
| 155 | `PersonalizedTextIcon` |
| 156 | `PinIcon` |
| 157 | `PlanFilledIcon` |
| 158 | `PlanIcon` |
| 159 | `PriceListFilledIcon` |
| 160 | `PriceListIcon` |
| 161 | `ProductCostIcon` |
| 162 | `ProductFilledIcon` |
| 163 | `ProductListIcon` |
| 164 | `ProductReferenceIcon` |
| 165 | `ProductUnavailableIcon` |
| 166 | `ReceiptDollarFilledIcon` |
| 167 | `ReceiptEuroFilledIcon` |
| 168 | `ReceiptPoundFilledIcon` |
| 169 | `ReceiptRupeeFilledIcon` |
| 170 | `ReceiptYenFilledIcon` |
| 171 | `RemoveBackgroundIcon` |
| 172 | `RewardIcon` |
| 173 | `RotateLeftIcon` |
| 174 | `RotateRightIcon` |
| 175 | `SettingsFilledIcon` |
| 176 | `ShippingLabelFilledIcon` |
| 177 | `ShippingLabelIcon` |
| 178 | `SidekickIcon` |
| 179 | `SkeletonIcon` |
| 180 | `StatusActiveIcon` |
| 181 | `StopCircleIcon` |
| 182 | `StoreFilledIcon` |
| 183 | `SunIcon` |
| 184 | `TargetFilledIcon` |
| 185 | `TaxFilledIcon` |
| 186 | `TextBoldIcon` |
| 187 | `TextColorIcon` |
| 188 | `TextFontListIcon` |
| 189 | `TextInRowsFilledIcon` |
| 190 | `TextInRowsIcon` |
| 191 | `TextIndentIcon` |
| 192 | `TextItalicIcon` |
| 193 | `TextUnderlineIcon` |
| 194 | `ToggleOffIcon` |
| 195 | `ToggleOnIcon` |
| 196 | `ViewportShortIcon` |
| 197 | `ViewportTallIcon` |
| 198 | `WalletFilledIcon` |
| 199 | `WorkFilledIcon` |

---

## 三、删除图标（v9 存在但 v13 无对应）

**无删除图标。** 所有 v9 图标在 v13 中都有对应的重命名版本。

---

## 四、数据来源

- **代码仓库**: [Shopify/polaris](https://github.com/Shopify/polaris-react)
- **v9 基准**: `@shopify/polaris@9.9.0` 对应 `@shopify/polaris-icons@4.22.0`
- **v13 基准**: `@shopify/polaris@13.9.5` 对应 `@shopify/polaris-icons@9.3.1`
- **迁移工具**: `polaris-migrator` 的 `icons-v8-update-names` 迁移
- **CHANGELOG**: `polaris-icons/CHANGELOG.md`
