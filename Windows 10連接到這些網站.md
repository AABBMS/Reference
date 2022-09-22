參考網站
https://tw.begin-it.com/8779-windows-10-connects-to-these-websites-after-a-clean-install


Windows 10為最終用戶提供了大量的隱私控制，他們可以隨意控制。如果要安裝Windows 10的全新副本，從版本1709及更高版本開始，Microsoft已發布其連接到哪些端點的詳細信息，我們認為您應該了解它。雖然我們已經知道無論何時連接到電子郵件服務器或瀏覽網頁或訪問存儲在雲上的備份，並使用該位置進行天氣預報，它們都會連接到相應的服務器，但之後還有更多內容。在完全安裝後，查看Windows 10連接到哪些網站和端點。

Windows 10連接的網站
---------------

當連接到不同的網站時，Windows用戶有很多方法。它包括在具有默認條件，空閒條件，全局接受的網絡協議分析器/捕獲工具的虛擬測試機器上設置Windows 10，並且還編譯有關流向公共IP地址的流量的報告。以下是與Windows 10 Enterprise連接的網站列表。

![](https://www.begin-it.com/media-content/windows/windows-10-connects-to-these-websites-after-a-clean-install.jpg)

**應用**

天氣App Live Tile。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| 探險者 | HTTP | tile-service.weather.microsoft.com | 1709 |
|     | HTTP | blob.weather.microsoft.com | 1803 |

OneNote Live Tile。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
|     | HTTPS | cdn.onenote.net/livetile/?Language=en-US | 1709 |

Twitter更新。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
|     | HTTPS | wildcard.twimg.com | 1709 |
| 中svchost.exe |     | oem.twimg.com/windows/tile.xml | 1709 |

Facebook更新。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
|     |     | star-mini.c10r.facebook.com | 1709 |

照片應用程序，用於下載配置文件，以及連接到Office 365門戶的共享基礎架構，包括Office Online

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| WindowsApps Microsoft.Windows.Photos | HTTPS | evoke-windowsservices-tas.msedge.net | 1709 |

Candy Crush Saga更新。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
|     | TLS v1.2 | candycrushsoda.king.com | 1709 |

Microsoft Wallet應用程序。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| SYSTEM32 AppHostRegistrationVerifier.exe | HTTPS | wallet.microsoft.com | 1709 |

Groove音樂應用

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| SYSTEM32 AppHostRegistrationVerifier.exe | HTTPS | mediaredirect.microsoft.com | 1709 |

**Cortana和搜索**

此網站或端點用於獲取用於Microsoft Store建議的圖像。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| searchui | HTTPS | store-images.s-microsoft.com | 1709 |

更新Cortana問候語，提示和活動磁貼。

(adsbygoogle = window.adsbygoogle || \[\]).push({});

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| backgroundtaskhost | HTTPS | www.bing.com/client | 1709 |

以下端點用於配置參數，例如Live Tile的更新頻率，以及啟用實驗功能。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| backgroundtaskhost | HTTPS | www.bing.com/proactive | 1709 |

Cortana使用該網站報告診斷和診斷數據信息

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| searchui **backgroundtaskhost** | HTTPS | www.bing.com/threshold/xls.aspx | 1709 |

**證書**

自動根證書更新組件使用此網站自動檢查Windows Update上的受信任權限列表，以查看是否有可用的更新。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| SVCHOST | HTTP | ctldl.windowsupdate.com | 1709 |

Windows使用此網站下載公開稱為欺詐的證書。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| SVCHOST | HTTP | ctldl.windowsupdate.com | 1709 |

**設備認證**

端點用於驗證設備。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
|     | HTTPS | login.live.com/ppsecure | 1709 |

**設備元數據**

為了檢索設備元數據。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
|     |     | dmd.metaservices.microsoft.com.akadns.net | 1709 |
|     | HTTP | dmd.metaservices.microsoft.com | 1803 |

**診斷數據**

以下端點由Connected User Experiences和Telemetry組件使用，並連接到Microsoft Data Management服務。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| SVCHOST |     | cy2.vortex.data.microsoft.com.akadns.net | 1709 |

連接的用戶體驗和遙測組件，並連接到Microsoft數據管理服務。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| SVCHOST |     | v10.vortex-win.data.microsoft.com/collect/v1 | 1709 |

Windows錯誤報告使用以下端點。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| wermgr |     | watson.telemetry.microsoft.com | 1709 |
|     | TLS v1.2 | modern.watson.data.microsoft.com.akadns.net | 1709 |

**字體流**

以下端點用於按需下載字體。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| SVCHOST |     | fs.microsoft.com | 1709 |
|     |     | fs.microsoft.com/fs/windows/config.json | 1709 |

**許可**

(adsbygoogle = window.adsbygoogle || \[\]).push({});

該網站用於在線激活和一些應用程序許可。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| LicenseManager有 | HTTPS | licensing.mp.microsoft.com/v7.0/licenses/content | 1709 |

**地點**

位置數據。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
|     | HTTP | location-inference-westus.cloudapp.net | 1709 |

**地圖**

以下端點用於檢查已下載以供脫機使用的映射的更新。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| SVCHOST | HTTPS | \* g.akamaiedge.net | 1709 |

**微軟帳戶**

以下端點用於Microsoft帳戶登錄。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
|     |     | login.msa.akadns6.net | 1709 |
| SYSTEM32 Auth.Host.exe | HTTPS | auth.gfx.ms | 1709 |

**Microsoft Store**

以下端點用於Windows推送通知服務（WNS）。 WNS使第三方開發人員能夠從他們自己的雲服務發送吐司，磁貼，徽章和原始更新。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
|     |     | \* .wns.windows.com | 1709 |

撤消Microsoft Store中惡意應用程序的許可證。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
|     | HTTP | storecatalogrevocation.storequality.microsoft.com | 1709 |

下載應用程序運行時調用的圖像文件（Microsoft Store或Inbox MSN Apps）。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
|     | HTTPS | img-prod-cms-rt-microsoft-com.akamaized.net | 1709 |
| backgroundtransferhost | HTTPS | store-images.microsoft.com | 1803 |

Windows通過這些與Microsoft Store進行通信

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
|     | HTTP | storeedgefd.dsx.mp.microsoft.com | 1709 |
|     | HTTP | pti.store.microsoft.com | 1709 |
|     | TLS v1.2 | CY2。*。md.mp.microsoft.com。*。 | 1709 |
| SVCHOST | HTTPS | displaycatalog.mp.microsoft.com | 1803 |

**網絡連接狀態指示燈（NCSI）**

網絡連接狀態指示器（NCSI）檢測Internet連接和公司網絡連接狀態。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
|     | HTTP | www.msftconnecttest.com/connecttest.txt | 1709 |

**辦公室**

以下端點用於連接Office 365門戶的共享基礎結構，包括Office Online。有關詳細信息，請參閱Office 365 URL和IP地址範圍。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
|     |     | \* .A-msedge.net | 1709 |
| hxstr |     | \* .C-msedge.net | 1709 |
|     |     | \* .E-msedge.net | 1709 |
|     |     | \* .S-msedge.net | 1709 |
|     | HTTPS | ocos-office365-s2s.msedge.net | 1803 |

以下端點用於連接Office 365門戶的共享基礎結構，包括Office Online。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| SYSTEM32 Auth.Host.exe | HTTPS | outlook.office365.com | 1709 |

以下端點是用於獲取Office應用程序元數據的OfficeHub流量。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| Windows Apps Microsoft.Windows.Photos | HTTPS | client-office365-tas.msedge.net | 1709 |

**一個驅動器**

Microsoft重定向服務使用這些服務自動更新URL。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| 一個驅動器 | HTTP HTTPS | g.live.com/1rewlive5skydrive/ODSUProduction | 1709 |

OneDrive for Business可從此處下載並驗證應用更新。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| 一個驅動器 | HTTPS | oneclient.sfx.ms | 1709 |

**設置**

以下端點用作應用程序動態更新其配置的方式。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| dmclient |     | cy2.settings.data.microsoft.com.akadns.net | 1709 |

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| dmclient | HTTPS | settings.data.microsoft.com | 1709 |

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| SVCHOST | HTTPS | settings-win.data.microsoft.com | 1709 |

**Skype的**

從這些端點下載Skype配置值。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| microsoft.windowscommunicationsapps.exe | HTTPS | config.edge.skype.com | 1709 |

**Windows Defender的**

Windows Defender通過這些啟用基於雲的保護。

(adsbygoogle = window.adsbygoogle || \[\]).push({});

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
|     |     | wdcp.microsoft.com | 1709 |

Windows Defender定義更新。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
|     |     | definitionupdates.microsoft.com | 1709 |
| 將MpCmdRun.exe | HTTPS | go.microsoft.com | 1709 |

**Windows Spotlight**

這些端點使Windows Spotlight元數據可用於圖像位置，以及建議的應用程序，Microsoft帳戶通知和Windows提示。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| backgroundtaskhost | HTTPS | arc.msn.com | 1709 |
| backgroundtaskhost |     | g.msn.com.nsatc.net | 1709 |
|     | TLS v1.2 | \* .search.msn.com | 1709 |
|     | HTTPS | ris.api.iris.microsoft.com | 1709 |
|     | HTTPS | query.prod.cms.rt.microsoft.com | 1709 |

**Windows更新**

以下端點用於Windows Update下載應用程序和操作系統更新，包括HTTP下載或與同行混合的HTTP下載。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| SVCHOST | HTTPS | \* .prod.do.dsp.mp.microsoft.com | 1709 |

Windows使用這些端點下載操作系統修補程序和更新。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| SVCHOST | HTTP | \* .windowsupdate.com | 1709 |
|     | HTTP | fg.download.windowsupdate.com.c.footprint.net | 1709 |

Highwinds Content Delivery Network使用這些來執行Windows更新。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
|     |     | cds.d2s7q6s2.hwcdn.net | 1709 |

Verizon Content Delivery Network使用這些來執行Windows更新。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
|     | HTTP | \* wac.phicdn.net | 1709 |
|     |     | \* wac.edgecastcdn.net | 1709 |

此網站或端點用於從Microsoft Store下載應用程序和Windows Insider預覽版本。時間限制URL（TLU）是一種保護內容的機制。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| SVCHOST |     | \* .tlu.dl.delivery.mp.microsoft.com.c.footprint.net | 1709 |

以下端點用於從Microsoft Store下載應用程序。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| SVCHOST |     | emdl.ws.microsoft.com | 1709 |

以下端點啟用與Windows Update，Microsoft Update和Store的聯機服務的連接。

(adsbygoogle = window.adsbygoogle || \[\]).push({});

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| SVCHOST | HTTPS | fe2.update.microsoft.com | 1709 |
| SVCHOST |     | fe3.delivery.mp.microsoft.com | 1709 |
|     |     | fe3.delivery.dsp.mp.microsoft.com.nsatc.net | 1709 |
| SVCHOST | HTTPS | sls.update.microsoft.com | 1709 |
|     | HTTP | \* .dl.delivery.mp.microsoft.com | 1803 |

以下端點用於內容監管。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| SVCHOST | HTTPS | tsfe.trafficshaping.dsp.mp.microsoft.com | 1709 |

以下端點用於下載內容。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
|     |     | a122.dscd.akamai.net | 1709 |
|     |     | a1621.g.akamai.net | 1709 |

**Microsoft前向鏈接重定向服務（FWLink）**

Microsoft前向鏈接重定向服務使用下面提到的網站將永久Web鏈接重定向到實際的，有時是短暫的URL。 FWlinks類似於URL縮短器，只是更長。

|     |     |     |     |
| --- | --- | --- | --- |
| 來源流程 | 協議  | 目的地 | 適用於Windows 10版本 |
| 各個  | HTTPS | go.microsoft.com | 1709 |

有關此內容的完整詳細信息以及如何關閉特定端點的流量，請訪問docs.microsoft.com。

* [Windows 10連接的網站](#6RI3TCQUZ7)
