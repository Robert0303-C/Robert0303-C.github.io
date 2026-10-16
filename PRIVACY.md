# Privacy Policy — Screen Recorder (Chunked Screen Recorder)

Last updated: 2026-10-16

## The short version

**Nothing you record ever leaves your computer. There is no server.**

## What the extension does with your screen content

When you start a recording, the extension captures the contents of the tab you
selected (and audio only if you asked for it). That data is:

- encoded on your own machine, and
- written directly to your own disk, in fragments, every half second.

Completed recordings are saved wherever you choose in the "Save as" dialog.
Unfinished recordings stay in your browser's private storage on your own disk
and are offered to you for recovery the next time you open the extension.

**Screen content is never transmitted anywhere.** The extension makes no network
requests of any kind — no analytics, no crash reporting, no update pings, no
advertising, no cloud sync. (The only `fetch` in the package reads the
extension's own bundled translation files from a `chrome-extension://` URL — a
local file inside the extension, never the network.)

**Microphone (optional — off unless you switch it on).** The microphone switch in
the popup is the only thing that turns the microphone on, and the first time you
flip it you are taken to a page that asks for the permission once. While it is
on, your voice is mixed with the tab's audio on your own machine, written to the
same local file, and released the moment the recording stops. Unless you turn
that switch on, no microphone is opened at all. Voice audio is never transmitted
anywhere.

## What we collect

Nothing.

- No account, no email, no sign-in.
- No usage statistics, no telemetry, no device identifiers.
- No cookies, no tracking pixels.
- No audio or video is uploaded. Your voice, like the screen, is only ever
  written to your own disk.

The developer receives no information about you or about what you record.

## Permissions, and why each one exists

| Permission | Why it is needed |
|---|---|
| `tabCapture` | Capture the contents of the tab you choose to record. This is the core function. |
| `offscreen` | Run the recorder in a hidden document so recording continues even if you close the popup. |
| `downloads` | Save the finished video file to the location you pick. |
| `notifications` | Show the recording status and the result of a save in a desktop notification, so you can see what is happening without keeping the popup open. |
| `activeTab` | Read the title and address of the tab you are on when you click the extension icon, so the recorder knows which tab you mean. Granted only at that moment. |
| `audioCapture` | Mix your spoken commentary (microphone) into the recording when you turn that switch on. Declared at install because Chromium does not allow this permission to be requested at runtime, but it is used only while the switch is on — with it off, the microphone is never opened, and recordings still work exactly the same. |

The extension requests no host permissions whatsoever. It cannot read or modify
any website.

## Third parties

There are none. No data is shared, sold, or transferred, because no data is
collected in the first place.

## Children's privacy

The extension collects no personal information from anyone, including children
under 13.

## Changes

If this policy ever changes, the updated version will be posted at this URL and
the "Last updated" date above will change.

## Contact

Questions about this policy: a21716423@gmail.com

---
---

# 隐私政策（中文版）

最后更新：2026-10-13

## 一句话总结

**你录的任何东西都不会离开你的电脑。没有服务器。**

## 扩展怎么处理你的屏幕内容

开始录制后，扩展会捕获你选中的那个标签页的画面（以及你要求时的声音）。这些数据：

- 在你自己的电脑上编码；
- 每半秒一次，直接写进你自己的硬盘。

录完的文件保存在你"另存为"时选的位置。没录完的内容留在你本机浏览器的私有存储里，
下次打开扩展时会提示你恢复。

**屏幕内容不会被发送到任何地方。** 扩展不发起任何网络请求 ——
没有统计、没有崩溃上报、没有更新检查、没有广告、没有云同步。
（包里唯一一处 `fetch` 读的是扩展自己打包进去的翻译文件，`chrome-extension://` 本机文件，
从不走网络。）

**麦克风（可选 —— 开关不开就不会用到）。** 只有弹窗里那个麦克风开关能打开它；
第一次打开开关时，会带你去一个页面授权一次。开关打开期间，你的解说和你本机上的
页面声音混合，写进同一个本地文件；录制一停止，麦克风立刻释放。
开关不开，就不会打开麦克风。语音同样不会发送到任何地方。

## 我们收集什么

什么都不收集。

- 不用注册、不要邮箱、不用登录
- 没有使用统计、没有设备标识
- 没有 cookie、没有跟踪
- 不上传任何音频或视频：你的声音和画面一样，只写进你自己的硬盘

开发者收不到关于你、或关于你录了什么的任何信息。

## 权限说明（每个都要用到）

| 权限 | 为什么需要 |
|---|---|
| `tabCapture` | 捕获你选择录制的那个标签页。这是核心功能。 |
| `offscreen` | 在隐藏文档里跑录制器，这样关掉弹窗录制也不会中断。 |
| `downloads` | 把录好的文件保存到你选的位置。 |
| `notifications` | 用桌面通知显示录制状态和保存结果，这样不用一直开着弹窗也能知道在发生什么。 |
| `activeTab` | 你点扩展图标时，读取当前标签页的标题和地址，好让录制知道你要录哪一个。只在这一刻临时授权。 |
| `audioCapture` | 打开麦克风开关时，把你的解说混进录制文件。因为它**不允许**在运行时申请，只能声明成安装时权限；但只有开关打开时才会用到 —— 开关关着时根本不打开麦克风，录制功能完全不受影响。 |

扩展**没有申请任何网站访问权限**，它无法读取或修改任何网页。

## 第三方

没有。数据不会被共享、出售或转移 —— 因为根本没有收集。

## 联系方式

关于本政策的问题：a21716423@gmail.com
