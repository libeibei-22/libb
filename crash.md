--------- beginning of crash
09-01 03:34:59.704 E/AndroidRuntime( 5195): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-01 03:34:59.704 E/AndroidRuntime( 5195): Process: com.tencent.qqpimsecure, PID: 5195
09-01 03:34:59.704 E/AndroidRuntime( 5195): java.lang.InternalError: Thread starting during runtime shutdown
09-01 03:34:59.704 E/AndroidRuntime( 5195): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 03:34:59.704 E/AndroidRuntime( 5195): 	at java.lang.Thread.start(Thread.java:733)
09-01 03:34:59.704 E/AndroidRuntime( 5195): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 03:34:59.704 E/AndroidRuntime( 5195): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 03:34:59.704 E/AndroidRuntime( 5195): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 03:34:59.704 E/AndroidRuntime( 5195): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 03:34:59.704 E/AndroidRuntime( 5195): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 03:34:59.704 E/AndroidRuntime( 5195): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 03:34:59.704 E/AndroidRuntime( 5195): 	at tcs.bca.<init>(SourceFile:24)
09-01 03:34:59.704 E/AndroidRuntime( 5195): 	at tcs.bcb.dv(SourceFile:157)
09-01 03:34:59.704 E/AndroidRuntime( 5195): 	at tcs.bcb.b(SourceFile:135)
09-01 03:34:59.704 E/AndroidRuntime( 5195): 	at tcs.bcb.uF(SourceFile:229)
09-01 03:34:59.704 E/AndroidRuntime( 5195): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-01 03:34:59.704 E/AndroidRuntime( 5195): 	at android.os.Handler.handleCallback(Handler.java:790)
09-01 03:34:59.704 E/AndroidRuntime( 5195): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-01 03:34:59.704 E/AndroidRuntime( 5195): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-01 03:34:59.704 E/AndroidRuntime( 5195): 	at android.os.Looper.loop(Looper.java:164)
09-01 03:34:59.704 E/AndroidRuntime( 5195): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 03:34:59.704 E/AndroidRuntime( 5195): 	at tcs.alk.run(SourceFile:79)
09-01 03:34:59.723 E/AndroidRuntime( 5195): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-01 03:34:59.723 E/AndroidRuntime( 5195): Process: com.tencent.qqpimsecure, PID: 5195
09-01 03:34:59.723 E/AndroidRuntime( 5195): java.lang.reflect.UndeclaredThrowableException
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at $Proxy6.getPreferenceService(Unknown Source)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at epmt.j.c(SourceFile:1)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at epmt.c.a(SourceFile:2)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at epmt.g.l(SourceFile:99)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at epmt.g.a(SourceFile:2)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at epmt.g$c.handleMessage(SourceFile:1)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at android.os.Looper.loop(Looper.java:164)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at tcs.alk.run(SourceFile:79)
09-01 03:34:59.723 E/AndroidRuntime( 5195): Caused by: java.lang.reflect.InvocationTargetException
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	... 10 more
09-01 03:34:59.723 E/AndroidRuntime( 5195): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at java.lang.Thread.start(Thread.java:733)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at tcs.eiv.aq(SourceFile:111)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at tcs.ahr.<init>(SourceFile:16)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-01 03:34:59.723 E/AndroidRuntime( 5195): 	... 13 more
09-01 03:35:04.602 E/AndroidRuntime( 5520): FATAL EXCEPTION: main
09-01 03:35:04.602 E/AndroidRuntime( 5520): Process: com.tencent.qqpimsecure, PID: 5520
09-01 03:35:04.602 E/AndroidRuntime( 5520): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at android.os.Looper.loop(Looper.java:164)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 03:35:04.602 E/AndroidRuntime( 5520): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	... 8 more
09-01 03:35:04.602 E/AndroidRuntime( 5520): Caused by: java.lang.reflect.UndeclaredThrowableException
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at $Proxy5.init(Unknown Source)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	... 12 more
09-01 03:35:04.602 E/AndroidRuntime( 5520): Caused by: java.lang.reflect.InvocationTargetException
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	... 16 more
09-01 03:35:04.602 E/AndroidRuntime( 5520): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{df7a74c u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at epetrp.b.c(SourceFile:8)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	at epetrp.c.init(SourceFile:1)
09-01 03:35:04.602 E/AndroidRuntime( 5520): 	... 19 more
09-01 03:35:09.589 E/AndroidRuntime( 5520): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-01 03:35:09.589 E/AndroidRuntime( 5520): Process: com.tencent.qqpimsecure, PID: 5520
09-01 03:35:09.589 E/AndroidRuntime( 5520): java.lang.InternalError: Thread starting during runtime shutdown
09-01 03:35:09.589 E/AndroidRuntime( 5520): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 03:35:09.589 E/AndroidRuntime( 5520): 	at java.lang.Thread.start(Thread.java:733)
09-01 03:35:09.589 E/AndroidRuntime( 5520): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 03:35:09.589 E/AndroidRuntime( 5520): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 03:35:09.589 E/AndroidRuntime( 5520): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 03:35:09.589 E/AndroidRuntime( 5520): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 03:35:09.589 E/AndroidRuntime( 5520): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 03:35:09.589 E/AndroidRuntime( 5520): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 03:35:09.589 E/AndroidRuntime( 5520): 	at tcs.bca.<init>(SourceFile:24)
09-01 03:35:09.589 E/AndroidRuntime( 5520): 	at tcs.bcb.dv(SourceFile:157)
09-01 03:35:09.589 E/AndroidRuntime( 5520): 	at tcs.bcb.b(SourceFile:135)
09-01 03:35:09.589 E/AndroidRuntime( 5520): 	at tcs.bcb.uF(SourceFile:229)
09-01 03:35:09.589 E/AndroidRuntime( 5520): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-01 03:35:09.589 E/AndroidRuntime( 5520): 	at android.os.Handler.handleCallback(Handler.java:790)
09-01 03:35:09.589 E/AndroidRuntime( 5520): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-01 03:35:09.589 E/AndroidRuntime( 5520): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-01 03:35:09.589 E/AndroidRuntime( 5520): 	at android.os.Looper.loop(Looper.java:164)
09-01 03:35:09.589 E/AndroidRuntime( 5520): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 03:35:09.589 E/AndroidRuntime( 5520): 	at tcs.alk.run(SourceFile:79)
09-01 03:35:09.610 E/AndroidRuntime( 5520): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-01 03:35:09.610 E/AndroidRuntime( 5520): Process: com.tencent.qqpimsecure, PID: 5520
09-01 03:35:09.610 E/AndroidRuntime( 5520): java.lang.reflect.UndeclaredThrowableException
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at $Proxy6.getPreferenceService(Unknown Source)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at epmt.j.c(SourceFile:1)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at epmt.c.a(SourceFile:2)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at epmt.g.l(SourceFile:99)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at epmt.g.a(SourceFile:2)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at epmt.g$c.handleMessage(SourceFile:1)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at android.os.Looper.loop(Looper.java:164)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at tcs.alk.run(SourceFile:79)
09-01 03:35:09.610 E/AndroidRuntime( 5520): Caused by: java.lang.reflect.InvocationTargetException
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	... 10 more
09-01 03:35:09.610 E/AndroidRuntime( 5520): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at java.lang.Thread.start(Thread.java:733)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at tcs.eiv.aq(SourceFile:111)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at tcs.ahr.<init>(SourceFile:16)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-01 03:35:09.610 E/AndroidRuntime( 5520): 	... 13 more
09-01 03:35:26.478 E/AndroidRuntime( 5729): FATAL EXCEPTION: main
09-01 03:35:26.478 E/AndroidRuntime( 5729): Process: com.tencent.qqpimsecure, PID: 5729
09-01 03:35:26.478 E/AndroidRuntime( 5729): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at android.os.Looper.loop(Looper.java:164)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 03:35:26.478 E/AndroidRuntime( 5729): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	... 8 more
09-01 03:35:26.478 E/AndroidRuntime( 5729): Caused by: java.lang.reflect.UndeclaredThrowableException
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at $Proxy5.init(Unknown Source)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	... 12 more
09-01 03:35:26.478 E/AndroidRuntime( 5729): Caused by: java.lang.reflect.InvocationTargetException
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	... 16 more
09-01 03:35:26.478 E/AndroidRuntime( 5729): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{8ca805b u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at epetrp.b.c(SourceFile:8)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	at epetrp.c.init(SourceFile:1)
09-01 03:35:26.478 E/AndroidRuntime( 5729): 	... 19 more
09-01 03:35:31.463 E/AndroidRuntime( 5729): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-01 03:35:31.463 E/AndroidRuntime( 5729): Process: com.tencent.qqpimsecure, PID: 5729
09-01 03:35:31.463 E/AndroidRuntime( 5729): java.lang.InternalError: Thread starting during runtime shutdown
09-01 03:35:31.463 E/AndroidRuntime( 5729): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 03:35:31.463 E/AndroidRuntime( 5729): 	at java.lang.Thread.start(Thread.java:733)
09-01 03:35:31.463 E/AndroidRuntime( 5729): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 03:35:31.463 E/AndroidRuntime( 5729): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 03:35:31.463 E/AndroidRuntime( 5729): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 03:35:31.463 E/AndroidRuntime( 5729): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 03:35:31.463 E/AndroidRuntime( 5729): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 03:35:31.463 E/AndroidRuntime( 5729): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 03:35:31.463 E/AndroidRuntime( 5729): 	at tcs.bca.<init>(SourceFile:24)
09-01 03:35:31.463 E/AndroidRuntime( 5729): 	at tcs.bcb.dv(SourceFile:157)
09-01 03:35:31.463 E/AndroidRuntime( 5729): 	at tcs.bcb.b(SourceFile:135)
09-01 03:35:31.463 E/AndroidRuntime( 5729): 	at tcs.bcb.uF(SourceFile:229)
09-01 03:35:31.463 E/AndroidRuntime( 5729): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-01 03:35:31.463 E/AndroidRuntime( 5729): 	at android.os.Handler.handleCallback(Handler.java:790)
09-01 03:35:31.463 E/AndroidRuntime( 5729): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-01 03:35:31.463 E/AndroidRuntime( 5729): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-01 03:35:31.463 E/AndroidRuntime( 5729): 	at android.os.Looper.loop(Looper.java:164)
09-01 03:35:31.463 E/AndroidRuntime( 5729): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 03:35:31.463 E/AndroidRuntime( 5729): 	at tcs.alk.run(SourceFile:79)
09-01 03:35:31.482 E/AndroidRuntime( 5729): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-01 03:35:31.482 E/AndroidRuntime( 5729): Process: com.tencent.qqpimsecure, PID: 5729
09-01 03:35:31.482 E/AndroidRuntime( 5729): java.lang.reflect.UndeclaredThrowableException
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at $Proxy6.getPreferenceService(Unknown Source)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at epmt.j.c(SourceFile:1)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at epmt.c.a(SourceFile:2)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at epmt.g.l(SourceFile:99)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at epmt.g.a(SourceFile:2)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at epmt.g$c.handleMessage(SourceFile:1)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at android.os.Looper.loop(Looper.java:164)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at tcs.alk.run(SourceFile:79)
09-01 03:35:31.482 E/AndroidRuntime( 5729): Caused by: java.lang.reflect.InvocationTargetException
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	... 10 more
09-01 03:35:31.482 E/AndroidRuntime( 5729): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at java.lang.Thread.start(Thread.java:733)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at tcs.eiv.aq(SourceFile:111)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at tcs.ahr.<init>(SourceFile:16)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-01 03:35:31.482 E/AndroidRuntime( 5729): 	... 13 more
09-01 03:36:36.317 E/AndroidRuntime( 6025): FATAL EXCEPTION: main
09-01 03:36:36.317 E/AndroidRuntime( 6025): Process: com.tencent.qqpimsecure, PID: 6025
09-01 03:36:36.317 E/AndroidRuntime( 6025): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at android.os.Looper.loop(Looper.java:164)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 03:36:36.317 E/AndroidRuntime( 6025): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	... 8 more
09-01 03:36:36.317 E/AndroidRuntime( 6025): Caused by: java.lang.reflect.UndeclaredThrowableException
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at $Proxy5.init(Unknown Source)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	... 12 more
09-01 03:36:36.317 E/AndroidRuntime( 6025): Caused by: java.lang.reflect.InvocationTargetException
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	... 16 more
09-01 03:36:36.317 E/AndroidRuntime( 6025): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{2ab816f u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at epetrp.b.c(SourceFile:8)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	at epetrp.c.init(SourceFile:1)
09-01 03:36:36.317 E/AndroidRuntime( 6025): 	... 19 more
09-01 03:36:41.294 E/AndroidRuntime( 6025): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-01 03:36:41.294 E/AndroidRuntime( 6025): Process: com.tencent.qqpimsecure, PID: 6025
09-01 03:36:41.294 E/AndroidRuntime( 6025): java.lang.InternalError: Thread starting during runtime shutdown
09-01 03:36:41.294 E/AndroidRuntime( 6025): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 03:36:41.294 E/AndroidRuntime( 6025): 	at java.lang.Thread.start(Thread.java:733)
09-01 03:36:41.294 E/AndroidRuntime( 6025): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 03:36:41.294 E/AndroidRuntime( 6025): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 03:36:41.294 E/AndroidRuntime( 6025): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 03:36:41.294 E/AndroidRuntime( 6025): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 03:36:41.294 E/AndroidRuntime( 6025): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 03:36:41.294 E/AndroidRuntime( 6025): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 03:36:41.294 E/AndroidRuntime( 6025): 	at tcs.bca.<init>(SourceFile:24)
09-01 03:36:41.294 E/AndroidRuntime( 6025): 	at tcs.bcb.dv(SourceFile:157)
09-01 03:36:41.294 E/AndroidRuntime( 6025): 	at tcs.bcb.b(SourceFile:135)
09-01 03:36:41.294 E/AndroidRuntime( 6025): 	at tcs.bcb.uF(SourceFile:229)
09-01 03:36:41.294 E/AndroidRuntime( 6025): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-01 03:36:41.294 E/AndroidRuntime( 6025): 	at android.os.Handler.handleCallback(Handler.java:790)
09-01 03:36:41.294 E/AndroidRuntime( 6025): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-01 03:36:41.294 E/AndroidRuntime( 6025): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-01 03:36:41.294 E/AndroidRuntime( 6025): 	at android.os.Looper.loop(Looper.java:164)
09-01 03:36:41.294 E/AndroidRuntime( 6025): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 03:36:41.294 E/AndroidRuntime( 6025): 	at tcs.alk.run(SourceFile:79)
09-01 03:36:41.323 E/AndroidRuntime( 6025): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-01 03:36:41.323 E/AndroidRuntime( 6025): Process: com.tencent.qqpimsecure, PID: 6025
09-01 03:36:41.323 E/AndroidRuntime( 6025): java.lang.reflect.UndeclaredThrowableException
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at $Proxy6.getPreferenceService(Unknown Source)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at epmt.j.c(SourceFile:1)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at epmt.c.a(SourceFile:2)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at epmt.g.l(SourceFile:99)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at epmt.g.a(SourceFile:2)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at epmt.g$c.handleMessage(SourceFile:1)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at android.os.Looper.loop(Looper.java:164)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at tcs.alk.run(SourceFile:79)
09-01 03:36:41.323 E/AndroidRuntime( 6025): Caused by: java.lang.reflect.InvocationTargetException
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	... 10 more
09-01 03:36:41.323 E/AndroidRuntime( 6025): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at java.lang.Thread.start(Thread.java:733)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at tcs.eiv.aq(SourceFile:111)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at tcs.ahr.<init>(SourceFile:16)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-01 03:36:41.323 E/AndroidRuntime( 6025): 	... 13 more
09-01 08:34:47.883 E/AndroidRuntime( 5773): FATAL EXCEPTION: main
09-01 08:34:47.883 E/AndroidRuntime( 5773): Process: com.tencent.qqpimsecure, PID: 5773
09-01 08:34:47.883 E/AndroidRuntime( 5773): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at android.os.Looper.loop(Looper.java:164)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 08:34:47.883 E/AndroidRuntime( 5773): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	... 8 more
09-01 08:34:47.883 E/AndroidRuntime( 5773): Caused by: java.lang.reflect.UndeclaredThrowableException
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at $Proxy5.init(Unknown Source)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	... 12 more
09-01 08:34:47.883 E/AndroidRuntime( 5773): Caused by: java.lang.reflect.InvocationTargetException
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	... 16 more
09-01 08:34:47.883 E/AndroidRuntime( 5773): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{3717fc6 u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at epetrp.b.c(SourceFile:8)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	at epetrp.c.init(SourceFile:1)
09-01 08:34:47.883 E/AndroidRuntime( 5773): 	... 19 more
09-01 08:34:52.863 E/AndroidRuntime( 5773): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-01 08:34:52.863 E/AndroidRuntime( 5773): Process: com.tencent.qqpimsecure, PID: 5773
09-01 08:34:52.863 E/AndroidRuntime( 5773): java.lang.InternalError: Thread starting during runtime shutdown
09-01 08:34:52.863 E/AndroidRuntime( 5773): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 08:34:52.863 E/AndroidRuntime( 5773): 	at java.lang.Thread.start(Thread.java:733)
09-01 08:34:52.863 E/AndroidRuntime( 5773): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 08:34:52.863 E/AndroidRuntime( 5773): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 08:34:52.863 E/AndroidRuntime( 5773): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 08:34:52.863 E/AndroidRuntime( 5773): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 08:34:52.863 E/AndroidRuntime( 5773): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 08:34:52.863 E/AndroidRuntime( 5773): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 08:34:52.863 E/AndroidRuntime( 5773): 	at tcs.bca.<init>(SourceFile:24)
09-01 08:34:52.863 E/AndroidRuntime( 5773): 	at tcs.bcb.dv(SourceFile:157)
09-01 08:34:52.863 E/AndroidRuntime( 5773): 	at tcs.bcb.b(SourceFile:135)
09-01 08:34:52.863 E/AndroidRuntime( 5773): 	at tcs.bcb.uF(SourceFile:229)
09-01 08:34:52.863 E/AndroidRuntime( 5773): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-01 08:34:52.863 E/AndroidRuntime( 5773): 	at android.os.Handler.handleCallback(Handler.java:790)
09-01 08:34:52.863 E/AndroidRuntime( 5773): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-01 08:34:52.863 E/AndroidRuntime( 5773): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-01 08:34:52.863 E/AndroidRuntime( 5773): 	at android.os.Looper.loop(Looper.java:164)
09-01 08:34:52.863 E/AndroidRuntime( 5773): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 08:34:52.863 E/AndroidRuntime( 5773): 	at tcs.alk.run(SourceFile:79)
09-01 08:34:52.886 E/AndroidRuntime( 5773): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-01 08:34:52.886 E/AndroidRuntime( 5773): Process: com.tencent.qqpimsecure, PID: 5773
09-01 08:34:52.886 E/AndroidRuntime( 5773): java.lang.reflect.UndeclaredThrowableException
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at $Proxy6.getPreferenceService(Unknown Source)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at epmt.j.c(SourceFile:1)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at epmt.c.a(SourceFile:2)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at epmt.g.l(SourceFile:99)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at epmt.g.a(SourceFile:2)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at epmt.g$c.handleMessage(SourceFile:1)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at android.os.Looper.loop(Looper.java:164)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at tcs.alk.run(SourceFile:79)
09-01 08:34:52.886 E/AndroidRuntime( 5773): Caused by: java.lang.reflect.InvocationTargetException
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	... 10 more
09-01 08:34:52.886 E/AndroidRuntime( 5773): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at java.lang.Thread.start(Thread.java:733)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at tcs.eiv.aq(SourceFile:111)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at tcs.ahr.<init>(SourceFile:16)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-01 08:34:52.886 E/AndroidRuntime( 5773): 	... 13 more
09-01 08:34:54.686 E/AndroidRuntime( 5984): FATAL EXCEPTION: main
09-01 08:34:54.686 E/AndroidRuntime( 5984): Process: com.tencent.qqpimsecure, PID: 5984
09-01 08:34:54.686 E/AndroidRuntime( 5984): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at android.os.Looper.loop(Looper.java:164)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 08:34:54.686 E/AndroidRuntime( 5984): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	... 8 more
09-01 08:34:54.686 E/AndroidRuntime( 5984): Caused by: java.lang.reflect.UndeclaredThrowableException
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at $Proxy5.init(Unknown Source)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	... 12 more
09-01 08:34:54.686 E/AndroidRuntime( 5984): Caused by: java.lang.reflect.InvocationTargetException
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	... 16 more
09-01 08:34:54.686 E/AndroidRuntime( 5984): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{2abcf6b u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at epetrp.b.c(SourceFile:8)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	at epetrp.c.init(SourceFile:1)
09-01 08:34:54.686 E/AndroidRuntime( 5984): 	... 19 more
09-01 08:34:59.672 E/AndroidRuntime( 5984): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-01 08:34:59.672 E/AndroidRuntime( 5984): Process: com.tencent.qqpimsecure, PID: 5984
09-01 08:34:59.672 E/AndroidRuntime( 5984): java.lang.InternalError: Thread starting during runtime shutdown
09-01 08:34:59.672 E/AndroidRuntime( 5984): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 08:34:59.672 E/AndroidRuntime( 5984): 	at java.lang.Thread.start(Thread.java:733)
09-01 08:34:59.672 E/AndroidRuntime( 5984): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 08:34:59.672 E/AndroidRuntime( 5984): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 08:34:59.672 E/AndroidRuntime( 5984): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 08:34:59.672 E/AndroidRuntime( 5984): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 08:34:59.672 E/AndroidRuntime( 5984): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 08:34:59.672 E/AndroidRuntime( 5984): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 08:34:59.672 E/AndroidRuntime( 5984): 	at tcs.bca.<init>(SourceFile:24)
09-01 08:34:59.672 E/AndroidRuntime( 5984): 	at tcs.bcb.dv(SourceFile:157)
09-01 08:34:59.672 E/AndroidRuntime( 5984): 	at tcs.bcb.b(SourceFile:135)
09-01 08:34:59.672 E/AndroidRuntime( 5984): 	at tcs.bcb.uF(SourceFile:229)
09-01 08:34:59.672 E/AndroidRuntime( 5984): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-01 08:34:59.672 E/AndroidRuntime( 5984): 	at android.os.Handler.handleCallback(Handler.java:790)
09-01 08:34:59.672 E/AndroidRuntime( 5984): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-01 08:34:59.672 E/AndroidRuntime( 5984): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-01 08:34:59.672 E/AndroidRuntime( 5984): 	at android.os.Looper.loop(Looper.java:164)
09-01 08:34:59.672 E/AndroidRuntime( 5984): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 08:34:59.672 E/AndroidRuntime( 5984): 	at tcs.alk.run(SourceFile:79)
09-01 08:34:59.692 E/AndroidRuntime( 5984): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-01 08:34:59.692 E/AndroidRuntime( 5984): Process: com.tencent.qqpimsecure, PID: 5984
09-01 08:34:59.692 E/AndroidRuntime( 5984): java.lang.reflect.UndeclaredThrowableException
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at $Proxy6.getPreferenceService(Unknown Source)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at epmt.j.c(SourceFile:1)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at epmt.c.a(SourceFile:2)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at epmt.g.l(SourceFile:99)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at epmt.g.a(SourceFile:2)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at epmt.g$c.handleMessage(SourceFile:1)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at android.os.Looper.loop(Looper.java:164)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at tcs.alk.run(SourceFile:79)
09-01 08:34:59.692 E/AndroidRuntime( 5984): Caused by: java.lang.reflect.InvocationTargetException
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	... 10 more
09-01 08:34:59.692 E/AndroidRuntime( 5984): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at java.lang.Thread.start(Thread.java:733)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at tcs.eiv.aq(SourceFile:111)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at tcs.ahr.<init>(SourceFile:16)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-01 08:34:59.692 E/AndroidRuntime( 5984): 	... 13 more
09-01 08:35:04.481 E/AndroidRuntime( 6188): FATAL EXCEPTION: main
09-01 08:35:04.481 E/AndroidRuntime( 6188): Process: com.tencent.qqpimsecure, PID: 6188
09-01 08:35:04.481 E/AndroidRuntime( 6188): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at android.os.Looper.loop(Looper.java:164)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 08:35:04.481 E/AndroidRuntime( 6188): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	... 8 more
09-01 08:35:04.481 E/AndroidRuntime( 6188): Caused by: java.lang.reflect.UndeclaredThrowableException
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at $Proxy5.init(Unknown Source)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	... 12 more
09-01 08:35:04.481 E/AndroidRuntime( 6188): Caused by: java.lang.reflect.InvocationTargetException
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	... 16 more
09-01 08:35:04.481 E/AndroidRuntime( 6188): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{19b8b71 u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at epetrp.b.c(SourceFile:8)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	at epetrp.c.init(SourceFile:1)
09-01 08:35:04.481 E/AndroidRuntime( 6188): 	... 19 more
09-01 08:35:09.474 E/AndroidRuntime( 6188): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-01 08:35:09.474 E/AndroidRuntime( 6188): Process: com.tencent.qqpimsecure, PID: 6188
09-01 08:35:09.474 E/AndroidRuntime( 6188): java.lang.InternalError: Thread starting during runtime shutdown
09-01 08:35:09.474 E/AndroidRuntime( 6188): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 08:35:09.474 E/AndroidRuntime( 6188): 	at java.lang.Thread.start(Thread.java:733)
09-01 08:35:09.474 E/AndroidRuntime( 6188): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 08:35:09.474 E/AndroidRuntime( 6188): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 08:35:09.474 E/AndroidRuntime( 6188): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 08:35:09.474 E/AndroidRuntime( 6188): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 08:35:09.474 E/AndroidRuntime( 6188): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 08:35:09.474 E/AndroidRuntime( 6188): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 08:35:09.474 E/AndroidRuntime( 6188): 	at tcs.bca.<init>(SourceFile:24)
09-01 08:35:09.474 E/AndroidRuntime( 6188): 	at tcs.bcb.dv(SourceFile:157)
09-01 08:35:09.474 E/AndroidRuntime( 6188): 	at tcs.bcb.b(SourceFile:135)
09-01 08:35:09.474 E/AndroidRuntime( 6188): 	at tcs.bcb.uF(SourceFile:229)
09-01 08:35:09.474 E/AndroidRuntime( 6188): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-01 08:35:09.474 E/AndroidRuntime( 6188): 	at android.os.Handler.handleCallback(Handler.java:790)
09-01 08:35:09.474 E/AndroidRuntime( 6188): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-01 08:35:09.474 E/AndroidRuntime( 6188): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-01 08:35:09.474 E/AndroidRuntime( 6188): 	at android.os.Looper.loop(Looper.java:164)
09-01 08:35:09.474 E/AndroidRuntime( 6188): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 08:35:09.474 E/AndroidRuntime( 6188): 	at tcs.alk.run(SourceFile:79)
09-01 08:35:09.494 E/AndroidRuntime( 6188): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-01 08:35:09.494 E/AndroidRuntime( 6188): Process: com.tencent.qqpimsecure, PID: 6188
09-01 08:35:09.494 E/AndroidRuntime( 6188): java.lang.reflect.UndeclaredThrowableException
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at $Proxy6.getPreferenceService(Unknown Source)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at epmt.j.c(SourceFile:1)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at epmt.c.a(SourceFile:2)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at epmt.g.l(SourceFile:99)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at epmt.g.a(SourceFile:2)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at epmt.g$c.handleMessage(SourceFile:1)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at android.os.Looper.loop(Looper.java:164)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at tcs.alk.run(SourceFile:79)
09-01 08:35:09.494 E/AndroidRuntime( 6188): Caused by: java.lang.reflect.InvocationTargetException
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	... 10 more
09-01 08:35:09.494 E/AndroidRuntime( 6188): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at java.lang.Thread.start(Thread.java:733)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at tcs.eiv.aq(SourceFile:111)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at tcs.ahr.<init>(SourceFile:16)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-01 08:35:09.494 E/AndroidRuntime( 6188): 	... 13 more
09-01 08:35:26.467 E/AndroidRuntime( 6374): FATAL EXCEPTION: main
09-01 08:35:26.467 E/AndroidRuntime( 6374): Process: com.tencent.qqpimsecure, PID: 6374
09-01 08:35:26.467 E/AndroidRuntime( 6374): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at android.os.Looper.loop(Looper.java:164)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 08:35:26.467 E/AndroidRuntime( 6374): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	... 8 more
09-01 08:35:26.467 E/AndroidRuntime( 6374): Caused by: java.lang.reflect.UndeclaredThrowableException
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at $Proxy5.init(Unknown Source)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	... 12 more
09-01 08:35:26.467 E/AndroidRuntime( 6374): Caused by: java.lang.reflect.InvocationTargetException
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	... 16 more
09-01 08:35:26.467 E/AndroidRuntime( 6374): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{c111db4 u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at epetrp.b.c(SourceFile:8)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	at epetrp.c.init(SourceFile:1)
09-01 08:35:26.467 E/AndroidRuntime( 6374): 	... 19 more
09-01 08:35:31.460 E/AndroidRuntime( 6374): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-01 08:35:31.460 E/AndroidRuntime( 6374): Process: com.tencent.qqpimsecure, PID: 6374
09-01 08:35:31.460 E/AndroidRuntime( 6374): java.lang.InternalError: Thread starting during runtime shutdown
09-01 08:35:31.460 E/AndroidRuntime( 6374): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 08:35:31.460 E/AndroidRuntime( 6374): 	at java.lang.Thread.start(Thread.java:733)
09-01 08:35:31.460 E/AndroidRuntime( 6374): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 08:35:31.460 E/AndroidRuntime( 6374): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 08:35:31.460 E/AndroidRuntime( 6374): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 08:35:31.460 E/AndroidRuntime( 6374): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 08:35:31.460 E/AndroidRuntime( 6374): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 08:35:31.460 E/AndroidRuntime( 6374): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 08:35:31.460 E/AndroidRuntime( 6374): 	at tcs.bca.<init>(SourceFile:24)
09-01 08:35:31.460 E/AndroidRuntime( 6374): 	at tcs.bcb.dv(SourceFile:157)
09-01 08:35:31.460 E/AndroidRuntime( 6374): 	at tcs.bcb.b(SourceFile:135)
09-01 08:35:31.460 E/AndroidRuntime( 6374): 	at tcs.bcb.uF(SourceFile:229)
09-01 08:35:31.460 E/AndroidRuntime( 6374): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-01 08:35:31.460 E/AndroidRuntime( 6374): 	at android.os.Handler.handleCallback(Handler.java:790)
09-01 08:35:31.460 E/AndroidRuntime( 6374): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-01 08:35:31.460 E/AndroidRuntime( 6374): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-01 08:35:31.460 E/AndroidRuntime( 6374): 	at android.os.Looper.loop(Looper.java:164)
09-01 08:35:31.460 E/AndroidRuntime( 6374): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 08:35:31.460 E/AndroidRuntime( 6374): 	at tcs.alk.run(SourceFile:79)
09-01 08:35:31.472 E/AndroidRuntime( 6374): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-01 08:35:31.472 E/AndroidRuntime( 6374): Process: com.tencent.qqpimsecure, PID: 6374
09-01 08:35:31.472 E/AndroidRuntime( 6374): java.lang.reflect.UndeclaredThrowableException
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at $Proxy6.getPreferenceService(Unknown Source)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at epmt.j.c(SourceFile:1)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at epmt.c.a(SourceFile:2)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at epmt.g.l(SourceFile:99)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at epmt.g.a(SourceFile:2)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at epmt.g$c.handleMessage(SourceFile:1)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at android.os.Looper.loop(Looper.java:164)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at tcs.alk.run(SourceFile:79)
09-01 08:35:31.472 E/AndroidRuntime( 6374): Caused by: java.lang.reflect.InvocationTargetException
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	... 10 more
09-01 08:35:31.472 E/AndroidRuntime( 6374): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at java.lang.Thread.start(Thread.java:733)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at tcs.eiv.aq(SourceFile:111)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at tcs.ahr.<init>(SourceFile:16)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-01 08:35:31.472 E/AndroidRuntime( 6374): 	... 13 more
09-01 08:36:36.309 E/AndroidRuntime( 6669): FATAL EXCEPTION: main
09-01 08:36:36.309 E/AndroidRuntime( 6669): Process: com.tencent.qqpimsecure, PID: 6669
09-01 08:36:36.309 E/AndroidRuntime( 6669): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at android.os.Looper.loop(Looper.java:164)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 08:36:36.309 E/AndroidRuntime( 6669): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	... 8 more
09-01 08:36:36.309 E/AndroidRuntime( 6669): Caused by: java.lang.reflect.UndeclaredThrowableException
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at $Proxy5.init(Unknown Source)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	... 12 more
09-01 08:36:36.309 E/AndroidRuntime( 6669): Caused by: java.lang.reflect.InvocationTargetException
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	... 16 more
09-01 08:36:36.309 E/AndroidRuntime( 6669): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{bbb6278 u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at epetrp.b.c(SourceFile:8)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	at epetrp.c.init(SourceFile:1)
09-01 08:36:36.309 E/AndroidRuntime( 6669): 	... 19 more
09-01 08:36:41.294 E/AndroidRuntime( 6669): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-01 08:36:41.294 E/AndroidRuntime( 6669): Process: com.tencent.qqpimsecure, PID: 6669
09-01 08:36:41.294 E/AndroidRuntime( 6669): java.lang.InternalError: Thread starting during runtime shutdown
09-01 08:36:41.294 E/AndroidRuntime( 6669): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 08:36:41.294 E/AndroidRuntime( 6669): 	at java.lang.Thread.start(Thread.java:733)
09-01 08:36:41.294 E/AndroidRuntime( 6669): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 08:36:41.294 E/AndroidRuntime( 6669): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 08:36:41.294 E/AndroidRuntime( 6669): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 08:36:41.294 E/AndroidRuntime( 6669): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 08:36:41.294 E/AndroidRuntime( 6669): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 08:36:41.294 E/AndroidRuntime( 6669): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 08:36:41.294 E/AndroidRuntime( 6669): 	at tcs.bca.<init>(SourceFile:24)
09-01 08:36:41.294 E/AndroidRuntime( 6669): 	at tcs.bcb.dv(SourceFile:157)
09-01 08:36:41.294 E/AndroidRuntime( 6669): 	at tcs.bcb.b(SourceFile:135)
09-01 08:36:41.294 E/AndroidRuntime( 6669): 	at tcs.bcb.uF(SourceFile:229)
09-01 08:36:41.294 E/AndroidRuntime( 6669): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-01 08:36:41.294 E/AndroidRuntime( 6669): 	at android.os.Handler.handleCallback(Handler.java:790)
09-01 08:36:41.294 E/AndroidRuntime( 6669): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-01 08:36:41.294 E/AndroidRuntime( 6669): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-01 08:36:41.294 E/AndroidRuntime( 6669): 	at android.os.Looper.loop(Looper.java:164)
09-01 08:36:41.294 E/AndroidRuntime( 6669): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 08:36:41.294 E/AndroidRuntime( 6669): 	at tcs.alk.run(SourceFile:79)
09-01 08:36:41.314 E/AndroidRuntime( 6669): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-01 08:36:41.314 E/AndroidRuntime( 6669): Process: com.tencent.qqpimsecure, PID: 6669
09-01 08:36:41.314 E/AndroidRuntime( 6669): java.lang.reflect.UndeclaredThrowableException
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at $Proxy6.getPreferenceService(Unknown Source)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at epmt.j.c(SourceFile:1)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at epmt.c.a(SourceFile:2)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at epmt.g.l(SourceFile:99)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at epmt.g.a(SourceFile:2)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at epmt.g$c.handleMessage(SourceFile:1)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at android.os.Looper.loop(Looper.java:164)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at tcs.alk.run(SourceFile:79)
09-01 08:36:41.314 E/AndroidRuntime( 6669): Caused by: java.lang.reflect.InvocationTargetException
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	... 10 more
09-01 08:36:41.314 E/AndroidRuntime( 6669): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at java.lang.Thread.start(Thread.java:733)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at tcs.eiv.aq(SourceFile:111)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at tcs.ahr.<init>(SourceFile:16)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-01 08:36:41.314 E/AndroidRuntime( 6669): 	... 13 more
--------- beginning of system
09-01 13:48:05.199 E/AndroidRuntime(31040): FATAL EXCEPTION: main
09-01 13:48:05.199 E/AndroidRuntime(31040): Process: com.tencent.qqpimsecure, PID: 31040
09-01 13:48:05.199 E/AndroidRuntime(31040): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at android.os.Looper.loop(Looper.java:164)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 13:48:05.199 E/AndroidRuntime(31040): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	... 8 more
09-01 13:48:05.199 E/AndroidRuntime(31040): Caused by: java.lang.reflect.UndeclaredThrowableException
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at $Proxy5.init(Unknown Source)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	... 12 more
09-01 13:48:05.199 E/AndroidRuntime(31040): Caused by: java.lang.reflect.InvocationTargetException
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	... 16 more
09-01 13:48:05.199 E/AndroidRuntime(31040): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{cc9478 u0a77 TRNB idle change:uncached procs:1 seq(0,0,0)}
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at epetrp.b.c(SourceFile:8)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	at epetrp.c.init(SourceFile:1)
09-01 13:48:05.199 E/AndroidRuntime(31040): 	... 19 more
09-01 13:48:09.958 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher2.permission.READ_SETTINGS in package: com.tencent.mobileqq at: Binary XML file line #83
09-01 13:48:09.959 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WRITE_CONTACTS in package: com.tencent.mobileqq at: Binary XML file line #114
09-01 13:48:09.960 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #185
09-01 13:48:09.960 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CHANGE_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #192
09-01 13:48:09.960 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.INTERNET in package: com.tencent.mobileqq at: Binary XML file line #193
09-01 13:48:09.960 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #194
09-01 13:48:09.960 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_NETWORK_STATE in package: com.tencent.mobileqq at: Binary XML file line #195
09-01 13:48:09.960 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CAMERA in package: com.tencent.mobileqq at: Binary XML file line #199
09-01 13:48:09.960 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.tencent.mobileqq at: Binary XML file line #200
09-01 13:48:09.961 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WAKE_LOCK in package: com.tencent.mobileqq at: Binary XML file line #201
09-01 13:48:09.961 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher.permission.INSTALL_SHORTCUT in package: com.tencent.mobileqq at: Binary XML file line #202
09-01 13:48:09.961 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.RECEIVE_BOOT_COMPLETED in package: com.tencent.mobileqq at: Binary XML file line #203
09-01 13:48:09.961 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #205
09-01 13:48:09.974 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Android/data/com.tencent.mobileqq/Tencent/TMAssistantSDK/Download/com.tencent.mobileqq/AndroidBBPJQQ_8.8.17.5770_537084958_bbb5f11ab5cf828c12abf84c5b33db55.apk Binary XML file line #2062
09-01 13:48:10.180 E/AndroidRuntime(31040): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-01 13:48:10.180 E/AndroidRuntime(31040): Process: com.tencent.qqpimsecure, PID: 31040
09-01 13:48:10.180 E/AndroidRuntime(31040): java.lang.InternalError: Thread starting during runtime shutdown
09-01 13:48:10.180 E/AndroidRuntime(31040): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 13:48:10.180 E/AndroidRuntime(31040): 	at java.lang.Thread.start(Thread.java:733)
09-01 13:48:10.180 E/AndroidRuntime(31040): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 13:48:10.180 E/AndroidRuntime(31040): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 13:48:10.180 E/AndroidRuntime(31040): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 13:48:10.180 E/AndroidRuntime(31040): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 13:48:10.180 E/AndroidRuntime(31040): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 13:48:10.180 E/AndroidRuntime(31040): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 13:48:10.180 E/AndroidRuntime(31040): 	at tcs.bca.<init>(SourceFile:24)
09-01 13:48:10.180 E/AndroidRuntime(31040): 	at tcs.bcb.dv(SourceFile:157)
09-01 13:48:10.180 E/AndroidRuntime(31040): 	at tcs.bcb.b(SourceFile:135)
09-01 13:48:10.180 E/AndroidRuntime(31040): 	at tcs.bcb.uF(SourceFile:229)
09-01 13:48:10.180 E/AndroidRuntime(31040): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-01 13:48:10.180 E/AndroidRuntime(31040): 	at android.os.Handler.handleCallback(Handler.java:790)
09-01 13:48:10.180 E/AndroidRuntime(31040): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-01 13:48:10.180 E/AndroidRuntime(31040): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-01 13:48:10.180 E/AndroidRuntime(31040): 	at android.os.Looper.loop(Looper.java:164)
09-01 13:48:10.180 E/AndroidRuntime(31040): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 13:48:10.180 E/AndroidRuntime(31040): 	at tcs.alk.run(SourceFile:79)
09-01 13:48:10.204 E/AndroidRuntime(31040): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-01 13:48:10.204 E/AndroidRuntime(31040): Process: com.tencent.qqpimsecure, PID: 31040
09-01 13:48:10.204 E/AndroidRuntime(31040): java.lang.reflect.UndeclaredThrowableException
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at $Proxy6.getPreferenceService(Unknown Source)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at epmt.j.c(SourceFile:1)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at epmt.c.a(SourceFile:2)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at epmt.g.l(SourceFile:99)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at epmt.g.a(SourceFile:2)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at epmt.g$c.handleMessage(SourceFile:1)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at android.os.Looper.loop(Looper.java:164)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at tcs.alk.run(SourceFile:79)
09-01 13:48:10.204 E/AndroidRuntime(31040): Caused by: java.lang.reflect.InvocationTargetException
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	... 10 more
09-01 13:48:10.204 E/AndroidRuntime(31040): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at java.lang.Thread.start(Thread.java:733)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at tcs.eiv.aq(SourceFile:111)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at tcs.ahr.<init>(SourceFile:16)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-01 13:48:10.204 E/AndroidRuntime(31040): 	... 13 more
09-01 13:48:12.368 E/AndroidRuntime(31277): FATAL EXCEPTION: main
09-01 13:48:12.368 E/AndroidRuntime(31277): Process: com.tencent.qqpimsecure, PID: 31277
09-01 13:48:12.368 E/AndroidRuntime(31277): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at android.os.Looper.loop(Looper.java:164)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 13:48:12.368 E/AndroidRuntime(31277): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	... 8 more
09-01 13:48:12.368 E/AndroidRuntime(31277): Caused by: java.lang.reflect.UndeclaredThrowableException
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at $Proxy5.init(Unknown Source)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	... 12 more
09-01 13:48:12.368 E/AndroidRuntime(31277): Caused by: java.lang.reflect.InvocationTargetException
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	... 16 more
09-01 13:48:12.368 E/AndroidRuntime(31277): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{d82a9e5 u0a77 TRNB idle change:uncached procs:1 seq(0,0,0)}
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at epetrp.b.c(SourceFile:8)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	at epetrp.c.init(SourceFile:1)
09-01 13:48:12.368 E/AndroidRuntime(31277): 	... 19 more
09-01 13:48:13.366 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.qqpimsecure-6755.apk Binary XML file line #836
09-01 13:48:13.789 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.sohu.inputmethod.sogou1460.apk Binary XML file line #264
09-01 13:48:13.895 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.qqpimsecure-6790.apk Binary XML file line #834
09-01 13:48:14.002 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher2.permission.READ_SETTINGS in package: com.tencent.mobileqq at: Binary XML file line #81
09-01 13:48:14.003 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WRITE_CONTACTS in package: com.tencent.mobileqq at: Binary XML file line #112
09-01 13:48:14.003 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #183
09-01 13:48:14.004 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CHANGE_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #190
09-01 13:48:14.004 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.INTERNET in package: com.tencent.mobileqq at: Binary XML file line #191
09-01 13:48:14.004 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #192
09-01 13:48:14.004 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_NETWORK_STATE in package: com.tencent.mobileqq at: Binary XML file line #193
09-01 13:48:14.004 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CAMERA in package: com.tencent.mobileqq at: Binary XML file line #197
09-01 13:48:14.004 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.tencent.mobileqq at: Binary XML file line #198
09-01 13:48:14.004 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WAKE_LOCK in package: com.tencent.mobileqq at: Binary XML file line #199
09-01 13:48:14.004 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher.permission.INSTALL_SHORTCUT in package: com.tencent.mobileqq at: Binary XML file line #200
09-01 13:48:14.004 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.RECEIVE_BOOT_COMPLETED in package: com.tencent.mobileqq at: Binary XML file line #201
09-01 13:48:14.004 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #203
09-01 13:48:14.016 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.mobileqq1792.apk Binary XML file line #2077
09-01 13:48:14.169 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-01 13:48:14.169 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/WeiXin/yunting-pugongying-debug.apk Binary XML file line #74
09-01 13:48:14.184 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/WeiXin/yunting-pugongying-debug.apk Binary XML file line #1330
09-01 13:48:14.249 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-01 13:48:14.250 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/??????_6.32.0.8340.apk Binary XML file line #74
09-01 13:48:14.267 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/??????_6.32.0.8340.apk Binary XML file line #1319
09-01 13:48:14.287 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-01 13:48:14.289 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/??????_6.32.0.8340-1.apk Binary XML file line #74
09-01 13:48:14.303 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/??????_6.32.0.8340-1.apk Binary XML file line #1319
09-01 13:48:16.534 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-01 13:48:16.535 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/download/WeiXin/yunting-pugongying-debug.apk Binary XML file line #74
09-01 13:48:16.543 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/download/WeiXin/yunting-pugongying-debug.apk Binary XML file line #1330
09-01 13:48:16.557 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-01 13:48:16.558 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/download/??????_6.32.0.8340.apk Binary XML file line #74
09-01 13:48:16.567 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/download/??????_6.32.0.8340.apk Binary XML file line #1319
09-01 13:48:16.581 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-01 13:48:16.581 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/download/??????_6.32.0.8340-1.apk Binary XML file line #74
09-01 13:48:16.590 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/download/??????_6.32.0.8340-1.apk Binary XML file line #1319
09-01 13:48:17.348 E/AndroidRuntime(31277): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-01 13:48:17.348 E/AndroidRuntime(31277): Process: com.tencent.qqpimsecure, PID: 31277
09-01 13:48:17.348 E/AndroidRuntime(31277): java.lang.InternalError: Thread starting during runtime shutdown
09-01 13:48:17.348 E/AndroidRuntime(31277): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 13:48:17.348 E/AndroidRuntime(31277): 	at java.lang.Thread.start(Thread.java:733)
09-01 13:48:17.348 E/AndroidRuntime(31277): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 13:48:17.348 E/AndroidRuntime(31277): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 13:48:17.348 E/AndroidRuntime(31277): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 13:48:17.348 E/AndroidRuntime(31277): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 13:48:17.348 E/AndroidRuntime(31277): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 13:48:17.348 E/AndroidRuntime(31277): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 13:48:17.348 E/AndroidRuntime(31277): 	at tcs.bca.<init>(SourceFile:24)
09-01 13:48:17.348 E/AndroidRuntime(31277): 	at tcs.bcb.dv(SourceFile:157)
09-01 13:48:17.348 E/AndroidRuntime(31277): 	at tcs.bcb.b(SourceFile:135)
09-01 13:48:17.348 E/AndroidRuntime(31277): 	at tcs.bcb.uF(SourceFile:229)
09-01 13:48:17.348 E/AndroidRuntime(31277): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-01 13:48:17.348 E/AndroidRuntime(31277): 	at android.os.Handler.handleCallback(Handler.java:790)
09-01 13:48:17.348 E/AndroidRuntime(31277): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-01 13:48:17.348 E/AndroidRuntime(31277): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-01 13:48:17.348 E/AndroidRuntime(31277): 	at android.os.Looper.loop(Looper.java:164)
09-01 13:48:17.348 E/AndroidRuntime(31277): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 13:48:17.348 E/AndroidRuntime(31277): 	at tcs.alk.run(SourceFile:79)
09-01 13:48:17.367 E/AndroidRuntime(31277): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-01 13:48:17.367 E/AndroidRuntime(31277): Process: com.tencent.qqpimsecure, PID: 31277
09-01 13:48:17.367 E/AndroidRuntime(31277): java.lang.reflect.UndeclaredThrowableException
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at $Proxy6.getPreferenceService(Unknown Source)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at epmt.j.c(SourceFile:1)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at epmt.c.a(SourceFile:2)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at epmt.g.l(SourceFile:99)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at epmt.g.a(SourceFile:2)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at epmt.g$c.handleMessage(SourceFile:1)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at android.os.Looper.loop(Looper.java:164)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at tcs.alk.run(SourceFile:79)
09-01 13:48:17.367 E/AndroidRuntime(31277): Caused by: java.lang.reflect.InvocationTargetException
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	... 10 more
09-01 13:48:17.367 E/AndroidRuntime(31277): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at java.lang.Thread.start(Thread.java:733)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at tcs.eiv.aq(SourceFile:111)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at tcs.ahr.<init>(SourceFile:16)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-01 13:48:17.367 E/AndroidRuntime(31277): 	... 13 more
09-01 13:48:22.251 E/AndroidRuntime(31458): FATAL EXCEPTION: main
09-01 13:48:22.251 E/AndroidRuntime(31458): Process: com.tencent.qqpimsecure, PID: 31458
09-01 13:48:22.251 E/AndroidRuntime(31458): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at android.os.Looper.loop(Looper.java:164)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 13:48:22.251 E/AndroidRuntime(31458): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	... 8 more
09-01 13:48:22.251 E/AndroidRuntime(31458): Caused by: java.lang.reflect.UndeclaredThrowableException
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at $Proxy5.init(Unknown Source)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	... 12 more
09-01 13:48:22.251 E/AndroidRuntime(31458): Caused by: java.lang.reflect.InvocationTargetException
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	... 16 more
09-01 13:48:22.251 E/AndroidRuntime(31458): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{7d0afa9 u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at epetrp.b.c(SourceFile:8)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	at epetrp.c.init(SourceFile:1)
09-01 13:48:22.251 E/AndroidRuntime(31458): 	... 19 more
09-01 13:48:27.236 E/AndroidRuntime(31458): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-01 13:48:27.236 E/AndroidRuntime(31458): Process: com.tencent.qqpimsecure, PID: 31458
09-01 13:48:27.236 E/AndroidRuntime(31458): java.lang.InternalError: Thread starting during runtime shutdown
09-01 13:48:27.236 E/AndroidRuntime(31458): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 13:48:27.236 E/AndroidRuntime(31458): 	at java.lang.Thread.start(Thread.java:733)
09-01 13:48:27.236 E/AndroidRuntime(31458): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 13:48:27.236 E/AndroidRuntime(31458): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 13:48:27.236 E/AndroidRuntime(31458): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 13:48:27.236 E/AndroidRuntime(31458): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 13:48:27.236 E/AndroidRuntime(31458): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 13:48:27.236 E/AndroidRuntime(31458): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 13:48:27.236 E/AndroidRuntime(31458): 	at tcs.bca.<init>(SourceFile:24)
09-01 13:48:27.236 E/AndroidRuntime(31458): 	at tcs.bcb.dv(SourceFile:157)
09-01 13:48:27.236 E/AndroidRuntime(31458): 	at tcs.bcb.b(SourceFile:135)
09-01 13:48:27.236 E/AndroidRuntime(31458): 	at tcs.bcb.uF(SourceFile:229)
09-01 13:48:27.236 E/AndroidRuntime(31458): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-01 13:48:27.236 E/AndroidRuntime(31458): 	at android.os.Handler.handleCallback(Handler.java:790)
09-01 13:48:27.236 E/AndroidRuntime(31458): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-01 13:48:27.236 E/AndroidRuntime(31458): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-01 13:48:27.236 E/AndroidRuntime(31458): 	at android.os.Looper.loop(Looper.java:164)
09-01 13:48:27.236 E/AndroidRuntime(31458): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 13:48:27.236 E/AndroidRuntime(31458): 	at tcs.alk.run(SourceFile:79)
09-01 13:48:27.266 E/AndroidRuntime(31458): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-01 13:48:27.266 E/AndroidRuntime(31458): Process: com.tencent.qqpimsecure, PID: 31458
09-01 13:48:27.266 E/AndroidRuntime(31458): java.lang.reflect.UndeclaredThrowableException
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at $Proxy6.getPreferenceService(Unknown Source)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at epmt.j.c(SourceFile:1)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at epmt.c.a(SourceFile:2)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at epmt.g.l(SourceFile:99)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at epmt.g.a(SourceFile:2)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at epmt.g$c.handleMessage(SourceFile:1)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at android.os.Looper.loop(Looper.java:164)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at tcs.alk.run(SourceFile:79)
09-01 13:48:27.266 E/AndroidRuntime(31458): Caused by: java.lang.reflect.InvocationTargetException
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	... 10 more
09-01 13:48:27.266 E/AndroidRuntime(31458): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at java.lang.Thread.start(Thread.java:733)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at tcs.eiv.aq(SourceFile:111)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at tcs.ahr.<init>(SourceFile:16)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-01 13:48:27.266 E/AndroidRuntime(31458): 	... 13 more
09-01 13:48:44.385 E/AndroidRuntime(31617): FATAL EXCEPTION: main
09-01 13:48:44.385 E/AndroidRuntime(31617): Process: com.tencent.qqpimsecure, PID: 31617
09-01 13:48:44.385 E/AndroidRuntime(31617): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at android.os.Looper.loop(Looper.java:164)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 13:48:44.385 E/AndroidRuntime(31617): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	... 8 more
09-01 13:48:44.385 E/AndroidRuntime(31617): Caused by: java.lang.reflect.UndeclaredThrowableException
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at $Proxy6.init(Unknown Source)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	... 12 more
09-01 13:48:44.385 E/AndroidRuntime(31617): Caused by: java.lang.reflect.InvocationTargetException
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	... 16 more
09-01 13:48:44.385 E/AndroidRuntime(31617): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{d48608f u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at epetrp.b.c(SourceFile:8)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	at epetrp.c.init(SourceFile:1)
09-01 13:48:44.385 E/AndroidRuntime(31617): 	... 19 more
09-01 13:48:49.370 E/AndroidRuntime(31617): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-01 13:48:49.370 E/AndroidRuntime(31617): Process: com.tencent.qqpimsecure, PID: 31617
09-01 13:48:49.370 E/AndroidRuntime(31617): java.lang.InternalError: Thread starting during runtime shutdown
09-01 13:48:49.370 E/AndroidRuntime(31617): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 13:48:49.370 E/AndroidRuntime(31617): 	at java.lang.Thread.start(Thread.java:733)
09-01 13:48:49.370 E/AndroidRuntime(31617): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 13:48:49.370 E/AndroidRuntime(31617): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 13:48:49.370 E/AndroidRuntime(31617): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 13:48:49.370 E/AndroidRuntime(31617): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 13:48:49.370 E/AndroidRuntime(31617): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 13:48:49.370 E/AndroidRuntime(31617): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 13:48:49.370 E/AndroidRuntime(31617): 	at tcs.bca.<init>(SourceFile:24)
09-01 13:48:49.370 E/AndroidRuntime(31617): 	at tcs.bcb.dv(SourceFile:157)
09-01 13:48:49.370 E/AndroidRuntime(31617): 	at tcs.bcb.b(SourceFile:135)
09-01 13:48:49.370 E/AndroidRuntime(31617): 	at tcs.bcb.uF(SourceFile:229)
09-01 13:48:49.370 E/AndroidRuntime(31617): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-01 13:48:49.370 E/AndroidRuntime(31617): 	at android.os.Handler.handleCallback(Handler.java:790)
09-01 13:48:49.370 E/AndroidRuntime(31617): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-01 13:48:49.370 E/AndroidRuntime(31617): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-01 13:48:49.370 E/AndroidRuntime(31617): 	at android.os.Looper.loop(Looper.java:164)
09-01 13:48:49.370 E/AndroidRuntime(31617): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 13:48:49.370 E/AndroidRuntime(31617): 	at tcs.alk.run(SourceFile:79)
09-01 13:48:49.395 E/AndroidRuntime(31617): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-01 13:48:49.395 E/AndroidRuntime(31617): Process: com.tencent.qqpimsecure, PID: 31617
09-01 13:48:49.395 E/AndroidRuntime(31617): java.lang.reflect.UndeclaredThrowableException
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at $Proxy5.getPreferenceService(Unknown Source)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at epmt.j.c(SourceFile:1)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at epmt.c.a(SourceFile:2)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at epmt.g.l(SourceFile:99)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at epmt.g.a(SourceFile:2)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at epmt.g$c.handleMessage(SourceFile:1)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at android.os.Looper.loop(Looper.java:164)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at tcs.alk.run(SourceFile:79)
09-01 13:48:49.395 E/AndroidRuntime(31617): Caused by: java.lang.reflect.InvocationTargetException
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	... 10 more
09-01 13:48:49.395 E/AndroidRuntime(31617): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at java.lang.Thread.start(Thread.java:733)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at tcs.eiv.aq(SourceFile:111)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at tcs.ahr.<init>(SourceFile:16)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-01 13:48:49.395 E/AndroidRuntime(31617): 	... 13 more
09-01 13:49:54.559 E/AndroidRuntime(31823): FATAL EXCEPTION: main
09-01 13:49:54.559 E/AndroidRuntime(31823): Process: com.tencent.qqpimsecure, PID: 31823
09-01 13:49:54.559 E/AndroidRuntime(31823): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at android.os.Looper.loop(Looper.java:164)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 13:49:54.559 E/AndroidRuntime(31823): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	... 8 more
09-01 13:49:54.559 E/AndroidRuntime(31823): Caused by: java.lang.reflect.UndeclaredThrowableException
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at $Proxy5.init(Unknown Source)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	... 12 more
09-01 13:49:54.559 E/AndroidRuntime(31823): Caused by: java.lang.reflect.InvocationTargetException
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	... 16 more
09-01 13:49:54.559 E/AndroidRuntime(31823): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{778a7ba u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at epetrp.b.c(SourceFile:8)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	at epetrp.c.init(SourceFile:1)
09-01 13:49:54.559 E/AndroidRuntime(31823): 	... 19 more
09-01 13:49:59.516 E/AndroidRuntime(31823): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-01 13:49:59.516 E/AndroidRuntime(31823): Process: com.tencent.qqpimsecure, PID: 31823
09-01 13:49:59.516 E/AndroidRuntime(31823): java.lang.InternalError: Thread starting during runtime shutdown
09-01 13:49:59.516 E/AndroidRuntime(31823): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 13:49:59.516 E/AndroidRuntime(31823): 	at java.lang.Thread.start(Thread.java:733)
09-01 13:49:59.516 E/AndroidRuntime(31823): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 13:49:59.516 E/AndroidRuntime(31823): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 13:49:59.516 E/AndroidRuntime(31823): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 13:49:59.516 E/AndroidRuntime(31823): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 13:49:59.516 E/AndroidRuntime(31823): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 13:49:59.516 E/AndroidRuntime(31823): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 13:49:59.516 E/AndroidRuntime(31823): 	at tcs.bca.<init>(SourceFile:24)
09-01 13:49:59.516 E/AndroidRuntime(31823): 	at tcs.bcb.dv(SourceFile:157)
09-01 13:49:59.516 E/AndroidRuntime(31823): 	at tcs.bcb.b(SourceFile:135)
09-01 13:49:59.516 E/AndroidRuntime(31823): 	at tcs.bcb.uF(SourceFile:229)
09-01 13:49:59.516 E/AndroidRuntime(31823): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-01 13:49:59.516 E/AndroidRuntime(31823): 	at android.os.Handler.handleCallback(Handler.java:790)
09-01 13:49:59.516 E/AndroidRuntime(31823): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-01 13:49:59.516 E/AndroidRuntime(31823): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-01 13:49:59.516 E/AndroidRuntime(31823): 	at android.os.Looper.loop(Looper.java:164)
09-01 13:49:59.516 E/AndroidRuntime(31823): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 13:49:59.516 E/AndroidRuntime(31823): 	at tcs.alk.run(SourceFile:79)
09-01 13:49:59.561 E/AndroidRuntime(31823): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-01 13:49:59.561 E/AndroidRuntime(31823): Process: com.tencent.qqpimsecure, PID: 31823
09-01 13:49:59.561 E/AndroidRuntime(31823): java.lang.reflect.UndeclaredThrowableException
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at $Proxy6.getPreferenceService(Unknown Source)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at epmt.j.c(SourceFile:1)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at epmt.c.a(SourceFile:2)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at epmt.g.l(SourceFile:99)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at epmt.g.a(SourceFile:2)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at epmt.g$c.handleMessage(SourceFile:1)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at android.os.Looper.loop(Looper.java:164)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at tcs.alk.run(SourceFile:79)
09-01 13:49:59.561 E/AndroidRuntime(31823): Caused by: java.lang.reflect.InvocationTargetException
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	... 10 more
09-01 13:49:59.561 E/AndroidRuntime(31823): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at java.lang.Thread.start(Thread.java:733)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at tcs.eiv.aq(SourceFile:111)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at tcs.ahr.<init>(SourceFile:16)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-01 13:49:59.561 E/AndroidRuntime(31823): 	... 13 more
09-01 14:08:57.809 E/AndroidRuntime(  834): FATAL EXCEPTION: main
09-01 14:08:57.809 E/AndroidRuntime(  834): Process: com.topsec.topsap, PID: 834
09-01 14:08:57.809 E/AndroidRuntime(  834): java.lang.RuntimeException: Unable to start activity ComponentInfo{com.topsec.topsap/com.topsec.topsap.ui.home.HomeActivity}: java.lang.NullPointerException: Attempt to read from field 'boolean com.topsec.sslvpn.datadef.ServiceAuthCfg.m_emm' on a null object reference
09-01 14:08:57.809 E/AndroidRuntime(  834): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2778)
09-01 14:08:57.809 E/AndroidRuntime(  834): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2856)
09-01 14:08:57.809 E/AndroidRuntime(  834): 	at android.app.ActivityThread.-wrap11(Unknown Source:0)
09-01 14:08:57.809 E/AndroidRuntime(  834): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1589)
09-01 14:08:57.809 E/AndroidRuntime(  834): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 14:08:57.809 E/AndroidRuntime(  834): 	at android.os.Looper.loop(Looper.java:164)
09-01 14:08:57.809 E/AndroidRuntime(  834): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 14:08:57.809 E/AndroidRuntime(  834): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 14:08:57.809 E/AndroidRuntime(  834): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 14:08:57.809 E/AndroidRuntime(  834): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 14:08:57.809 E/AndroidRuntime(  834): Caused by: java.lang.NullPointerException: Attempt to read from field 'boolean com.topsec.sslvpn.datadef.ServiceAuthCfg.m_emm' on a null object reference
09-01 14:08:57.809 E/AndroidRuntime(  834): 	at com.topsec.topsap.common.utils.HomeTabData.initTabData(HomeTabData.java:44)
09-01 14:08:57.809 E/AndroidRuntime(  834): 	at com.topsec.topsap.common.utils.HomeTabData.<init>(HomeTabData.java:36)
09-01 14:08:57.809 E/AndroidRuntime(  834): 	at com.topsec.topsap.common.utils.HomeTabData.getInstance(HomeTabData.java:24)
09-01 14:08:57.809 E/AndroidRuntime(  834): 	at com.topsec.topsap.ui.home.HomeActivity.h(HomeActivity.java:172)
09-01 14:08:57.809 E/AndroidRuntime(  834): 	at com.topsec.topsap.ui.home.HomeActivity.i(HomeActivity.java:192)
09-01 14:08:57.809 E/AndroidRuntime(  834): 	at com.topsec.topsap.ui.home.HomeActivity.onCreate(HomeActivity.java:119)
09-01 14:08:57.809 E/AndroidRuntime(  834): 	at android.app.Activity.performCreate(Activity.java:7009)
09-01 14:08:57.809 E/AndroidRuntime(  834): 	at android.app.Activity.performCreate(Activity.java:7000)
09-01 14:08:57.809 E/AndroidRuntime(  834): 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1214)
09-01 14:08:57.809 E/AndroidRuntime(  834): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2731)
09-01 14:08:57.809 E/AndroidRuntime(  834): 	... 9 more
09-01 14:09:01.137 E/AndroidRuntime(  878): FATAL EXCEPTION: main
09-01 14:09:01.137 E/AndroidRuntime(  878): Process: com.topsec.topsap, PID: 878
09-01 14:09:01.137 E/AndroidRuntime(  878): java.lang.RuntimeException: Unable to start activity ComponentInfo{com.topsec.topsap/com.topsec.topsap.ui.home.HomeActivity}: java.lang.NullPointerException: Attempt to read from field 'boolean com.topsec.sslvpn.datadef.ServiceAuthCfg.m_emm' on a null object reference
09-01 14:09:01.137 E/AndroidRuntime(  878): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2778)
09-01 14:09:01.137 E/AndroidRuntime(  878): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2856)
09-01 14:09:01.137 E/AndroidRuntime(  878): 	at android.app.ActivityThread.-wrap11(Unknown Source:0)
09-01 14:09:01.137 E/AndroidRuntime(  878): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1589)
09-01 14:09:01.137 E/AndroidRuntime(  878): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 14:09:01.137 E/AndroidRuntime(  878): 	at android.os.Looper.loop(Looper.java:164)
09-01 14:09:01.137 E/AndroidRuntime(  878): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 14:09:01.137 E/AndroidRuntime(  878): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 14:09:01.137 E/AndroidRuntime(  878): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 14:09:01.137 E/AndroidRuntime(  878): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 14:09:01.137 E/AndroidRuntime(  878): Caused by: java.lang.NullPointerException: Attempt to read from field 'boolean com.topsec.sslvpn.datadef.ServiceAuthCfg.m_emm' on a null object reference
09-01 14:09:01.137 E/AndroidRuntime(  878): 	at com.topsec.topsap.common.utils.HomeTabData.initTabData(HomeTabData.java:44)
09-01 14:09:01.137 E/AndroidRuntime(  878): 	at com.topsec.topsap.common.utils.HomeTabData.<init>(HomeTabData.java:36)
09-01 14:09:01.137 E/AndroidRuntime(  878): 	at com.topsec.topsap.common.utils.HomeTabData.getInstance(HomeTabData.java:24)
09-01 14:09:01.137 E/AndroidRuntime(  878): 	at com.topsec.topsap.ui.home.HomeActivity.h(HomeActivity.java:172)
09-01 14:09:01.137 E/AndroidRuntime(  878): 	at com.topsec.topsap.ui.home.HomeActivity.i(HomeActivity.java:192)
09-01 14:09:01.137 E/AndroidRuntime(  878): 	at com.topsec.topsap.ui.home.HomeActivity.onCreate(HomeActivity.java:119)
09-01 14:09:01.137 E/AndroidRuntime(  878): 	at android.app.Activity.performCreate(Activity.java:7009)
09-01 14:09:01.137 E/AndroidRuntime(  878): 	at android.app.Activity.performCreate(Activity.java:7000)
09-01 14:09:01.137 E/AndroidRuntime(  878): 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1214)
09-01 14:09:01.137 E/AndroidRuntime(  878): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2731)
09-01 14:09:01.137 E/AndroidRuntime(  878): 	... 9 more
09-01 14:09:05.504 E/AndroidRuntime(  925): FATAL EXCEPTION: main
09-01 14:09:05.504 E/AndroidRuntime(  925): Process: com.topsec.topsap, PID: 925
09-01 14:09:05.504 E/AndroidRuntime(  925): java.lang.RuntimeException: Unable to start activity ComponentInfo{com.topsec.topsap/com.topsec.topsap.ui.home.HomeActivity}: java.lang.NullPointerException: Attempt to read from field 'boolean com.topsec.sslvpn.datadef.ServiceAuthCfg.m_emm' on a null object reference
09-01 14:09:05.504 E/AndroidRuntime(  925): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2778)
09-01 14:09:05.504 E/AndroidRuntime(  925): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2856)
09-01 14:09:05.504 E/AndroidRuntime(  925): 	at android.app.ActivityThread.-wrap11(Unknown Source:0)
09-01 14:09:05.504 E/AndroidRuntime(  925): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1589)
09-01 14:09:05.504 E/AndroidRuntime(  925): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 14:09:05.504 E/AndroidRuntime(  925): 	at android.os.Looper.loop(Looper.java:164)
09-01 14:09:05.504 E/AndroidRuntime(  925): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 14:09:05.504 E/AndroidRuntime(  925): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 14:09:05.504 E/AndroidRuntime(  925): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 14:09:05.504 E/AndroidRuntime(  925): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 14:09:05.504 E/AndroidRuntime(  925): Caused by: java.lang.NullPointerException: Attempt to read from field 'boolean com.topsec.sslvpn.datadef.ServiceAuthCfg.m_emm' on a null object reference
09-01 14:09:05.504 E/AndroidRuntime(  925): 	at com.topsec.topsap.common.utils.HomeTabData.initTabData(HomeTabData.java:44)
09-01 14:09:05.504 E/AndroidRuntime(  925): 	at com.topsec.topsap.common.utils.HomeTabData.<init>(HomeTabData.java:36)
09-01 14:09:05.504 E/AndroidRuntime(  925): 	at com.topsec.topsap.common.utils.HomeTabData.getInstance(HomeTabData.java:24)
09-01 14:09:05.504 E/AndroidRuntime(  925): 	at com.topsec.topsap.ui.home.HomeActivity.h(HomeActivity.java:172)
09-01 14:09:05.504 E/AndroidRuntime(  925): 	at com.topsec.topsap.ui.home.HomeActivity.i(HomeActivity.java:192)
09-01 14:09:05.504 E/AndroidRuntime(  925): 	at com.topsec.topsap.ui.home.HomeActivity.onCreate(HomeActivity.java:119)
09-01 14:09:05.504 E/AndroidRuntime(  925): 	at android.app.Activity.performCreate(Activity.java:7009)
09-01 14:09:05.504 E/AndroidRuntime(  925): 	at android.app.Activity.performCreate(Activity.java:7000)
09-01 14:09:05.504 E/AndroidRuntime(  925): 	at android.app.Instrumentation.callActivityOnCreate(Instrumentation.java:1214)
09-01 14:09:05.504 E/AndroidRuntime(  925): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2731)
09-01 14:09:05.504 E/AndroidRuntime(  925): 	... 9 more
09-01 14:09:24.185 W/FileUtils( 1230): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-01 14:09:24.194 W/FileUtils( 1230): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-01 14:09:24.206 W/FileUtils( 1230): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-01 14:09:24.209 W/FileUtils( 1230): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-01 14:09:24.575 W/FileUtils( 1230): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-01 14:09:24.579 W/FileUtils( 1230): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-01 14:09:24.625 W/FileUtils( 1230): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-01 14:09:24.633 W/FileUtils( 1230): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-01 14:09:28.739 E/ActivityThread( 1000): Failed to find provider info for com.vivo.push.sdk.service.SystemPushConfig
09-01 14:09:34.949 W/FileUtils( 1230): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-01 14:09:34.950 W/FileUtils( 1230): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-01 14:09:34.966 W/FileUtils( 1230): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-01 14:09:34.966 W/FileUtils( 1230): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-01 15:58:04.188 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher2.permission.READ_SETTINGS in package: com.tencent.mobileqq at: Binary XML file line #83
09-01 15:58:04.189 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WRITE_CONTACTS in package: com.tencent.mobileqq at: Binary XML file line #114
09-01 15:58:04.190 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #185
09-01 15:58:04.190 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CHANGE_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #192
09-01 15:58:04.190 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.INTERNET in package: com.tencent.mobileqq at: Binary XML file line #193
09-01 15:58:04.190 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #194
09-01 15:58:04.190 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_NETWORK_STATE in package: com.tencent.mobileqq at: Binary XML file line #195
09-01 15:58:04.190 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CAMERA in package: com.tencent.mobileqq at: Binary XML file line #199
09-01 15:58:04.190 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.tencent.mobileqq at: Binary XML file line #200
09-01 15:58:04.190 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WAKE_LOCK in package: com.tencent.mobileqq at: Binary XML file line #201
09-01 15:58:04.190 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher.permission.INSTALL_SHORTCUT in package: com.tencent.mobileqq at: Binary XML file line #202
09-01 15:58:04.190 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.RECEIVE_BOOT_COMPLETED in package: com.tencent.mobileqq at: Binary XML file line #203
09-01 15:58:04.190 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #205
09-01 15:58:04.218 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Android/data/com.tencent.mobileqq/Tencent/TMAssistantSDK/Download/com.tencent.mobileqq/AndroidBBPJQQ_8.8.17.5770_537084958_bbb5f11ab5cf828c12abf84c5b33db55.apk Binary XML file line #2062
09-01 15:58:04.345 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-01 15:58:04.346 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/WeiXin/yunting-pugongying-debug.apk Binary XML file line #74
09-01 15:58:04.355 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/WeiXin/yunting-pugongying-debug.apk Binary XML file line #1330
09-01 15:58:04.406 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-01 15:58:04.407 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/WeiXin/yunting-pugongying-debug.apk Binary XML file line #74
09-01 15:58:04.417 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/WeiXin/yunting-pugongying-debug.apk Binary XML file line #1330
09-01 15:58:04.434 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-01 15:58:04.435 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/??????_6.32.0.8340.apk Binary XML file line #74
09-01 15:58:04.444 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/??????_6.32.0.8340.apk Binary XML file line #1319
09-01 15:58:04.487 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-01 15:58:04.488 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/??????_6.32.0.8340.apk Binary XML file line #74
09-01 15:58:04.502 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/??????_6.32.0.8340.apk Binary XML file line #1319
09-01 15:58:04.525 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-01 15:58:04.525 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/??????_6.32.0.8340-1.apk Binary XML file line #74
09-01 15:58:04.536 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/??????_6.32.0.8340-1.apk Binary XML file line #1319
09-01 15:58:04.582 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-01 15:58:04.583 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/??????_6.32.0.8340-1.apk Binary XML file line #74
09-01 15:58:04.599 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/??????_6.32.0.8340-1.apk Binary XML file line #1319
09-01 15:58:06.727 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.qqpimsecure-6755.apk Binary XML file line #836
09-01 15:58:06.950 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.sohu.inputmethod.sogou1460.apk Binary XML file line #264
09-01 15:58:07.029 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.qqpimsecure-6790.apk Binary XML file line #834
09-01 15:58:07.116 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher2.permission.READ_SETTINGS in package: com.tencent.mobileqq at: Binary XML file line #81
09-01 15:58:07.117 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WRITE_CONTACTS in package: com.tencent.mobileqq at: Binary XML file line #112
09-01 15:58:07.117 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #183
09-01 15:58:07.117 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CHANGE_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #190
09-01 15:58:07.117 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.INTERNET in package: com.tencent.mobileqq at: Binary XML file line #191
09-01 15:58:07.117 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #192
09-01 15:58:07.118 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_NETWORK_STATE in package: com.tencent.mobileqq at: Binary XML file line #193
09-01 15:58:07.118 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CAMERA in package: com.tencent.mobileqq at: Binary XML file line #197
09-01 15:58:07.118 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.tencent.mobileqq at: Binary XML file line #198
09-01 15:58:07.118 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WAKE_LOCK in package: com.tencent.mobileqq at: Binary XML file line #199
09-01 15:58:07.118 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher.permission.INSTALL_SHORTCUT in package: com.tencent.mobileqq at: Binary XML file line #200
09-01 15:58:07.118 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.RECEIVE_BOOT_COMPLETED in package: com.tencent.mobileqq at: Binary XML file line #201
09-01 15:58:07.118 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #203
09-01 15:58:07.128 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.mobileqq1792.apk Binary XML file line #2077
09-01 15:58:07.238 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-01 15:58:07.238 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/WeiXin/yunting-pugongying-debug.apk Binary XML file line #74
09-01 15:58:07.248 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/WeiXin/yunting-pugongying-debug.apk Binary XML file line #1330
09-01 15:58:07.283 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-01 15:58:07.284 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/??????_6.32.0.8340.apk Binary XML file line #74
09-01 15:58:07.297 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/??????_6.32.0.8340.apk Binary XML file line #1319
09-01 15:58:07.313 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-01 15:58:07.314 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/??????_6.32.0.8340-1.apk Binary XML file line #74
09-01 15:58:07.323 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/??????_6.32.0.8340-1.apk Binary XML file line #1319
09-01 15:58:09.455 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-01 15:58:09.456 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/download/WeiXin/yunting-pugongying-debug.apk Binary XML file line #74
09-01 15:58:09.466 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/download/WeiXin/yunting-pugongying-debug.apk Binary XML file line #1330
09-01 15:58:09.484 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-01 15:58:09.485 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/download/??????_6.32.0.8340.apk Binary XML file line #74
09-01 15:58:09.493 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/download/??????_6.32.0.8340.apk Binary XML file line #1319
09-01 15:58:09.508 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-01 15:58:09.508 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/download/??????_6.32.0.8340-1.apk Binary XML file line #74
09-01 15:58:09.517 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/download/??????_6.32.0.8340-1.apk Binary XML file line #1319
09-01 17:04:25.065 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher2.permission.READ_SETTINGS in package: com.tencent.mobileqq at: Binary XML file line #83
09-01 17:04:25.066 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WRITE_CONTACTS in package: com.tencent.mobileqq at: Binary XML file line #114
09-01 17:04:25.067 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #185
09-01 17:04:25.067 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CHANGE_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #192
09-01 17:04:25.067 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.INTERNET in package: com.tencent.mobileqq at: Binary XML file line #193
09-01 17:04:25.067 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #194
09-01 17:04:25.067 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_NETWORK_STATE in package: com.tencent.mobileqq at: Binary XML file line #195
09-01 17:04:25.067 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CAMERA in package: com.tencent.mobileqq at: Binary XML file line #199
09-01 17:04:25.067 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.tencent.mobileqq at: Binary XML file line #200
09-01 17:04:25.067 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WAKE_LOCK in package: com.tencent.mobileqq at: Binary XML file line #201
09-01 17:04:25.067 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher.permission.INSTALL_SHORTCUT in package: com.tencent.mobileqq at: Binary XML file line #202
09-01 17:04:25.067 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.RECEIVE_BOOT_COMPLETED in package: com.tencent.mobileqq at: Binary XML file line #203
09-01 17:04:25.067 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #205
09-01 17:04:25.078 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Android/data/com.tencent.mobileqq/Tencent/TMAssistantSDK/Download/com.tencent.mobileqq/AndroidBBPJQQ_8.8.17.5770_537084958_bbb5f11ab5cf828c12abf84c5b33db55.apk Binary XML file line #2062
09-01 17:04:27.867 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.qqpimsecure-6755.apk Binary XML file line #836
09-01 17:04:28.094 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.sohu.inputmethod.sogou1460.apk Binary XML file line #264
09-01 17:04:28.174 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.qqpimsecure-6790.apk Binary XML file line #834
09-01 17:04:28.263 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher2.permission.READ_SETTINGS in package: com.tencent.mobileqq at: Binary XML file line #81
09-01 17:04:28.264 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WRITE_CONTACTS in package: com.tencent.mobileqq at: Binary XML file line #112
09-01 17:04:28.264 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #183
09-01 17:04:28.265 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CHANGE_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #190
09-01 17:04:28.265 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.INTERNET in package: com.tencent.mobileqq at: Binary XML file line #191
09-01 17:04:28.265 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #192
09-01 17:04:28.265 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_NETWORK_STATE in package: com.tencent.mobileqq at: Binary XML file line #193
09-01 17:04:28.265 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CAMERA in package: com.tencent.mobileqq at: Binary XML file line #197
09-01 17:04:28.265 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.tencent.mobileqq at: Binary XML file line #198
09-01 17:04:28.265 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WAKE_LOCK in package: com.tencent.mobileqq at: Binary XML file line #199
09-01 17:04:28.265 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher.permission.INSTALL_SHORTCUT in package: com.tencent.mobileqq at: Binary XML file line #200
09-01 17:04:28.265 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.RECEIVE_BOOT_COMPLETED in package: com.tencent.mobileqq at: Binary XML file line #201
09-01 17:04:28.265 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #203
09-01 17:04:28.276 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.mobileqq1792.apk Binary XML file line #2077
09-01 17:04:28.393 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-01 17:04:28.395 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/WeiXin/yunting-pugongying-debug.apk Binary XML file line #74
09-01 17:04:28.405 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/WeiXin/yunting-pugongying-debug.apk Binary XML file line #1330
09-01 17:04:28.442 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-01 17:04:28.442 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/??????_6.32.0.8340.apk Binary XML file line #74
09-01 17:04:28.453 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/??????_6.32.0.8340.apk Binary XML file line #1319
09-01 17:04:28.472 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-01 17:04:28.473 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/??????_6.32.0.8340-1.apk Binary XML file line #74
09-01 17:04:28.492 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/??????_6.32.0.8340-1.apk Binary XML file line #1319
09-01 17:04:30.887 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-01 17:04:30.888 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/download/WeiXin/yunting-pugongying-debug.apk Binary XML file line #74
09-01 17:04:30.898 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/download/WeiXin/yunting-pugongying-debug.apk Binary XML file line #1330
09-01 17:04:30.912 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-01 17:04:30.913 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/download/??????_6.32.0.8340.apk Binary XML file line #74
09-01 17:04:30.924 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/download/??????_6.32.0.8340.apk Binary XML file line #1319
09-01 17:04:30.939 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-01 17:04:30.940 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/download/??????_6.32.0.8340-1.apk Binary XML file line #74
09-01 17:04:30.950 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/download/??????_6.32.0.8340-1.apk Binary XML file line #1319
09-01 18:36:05.584 E/AndroidRuntime(  925): FATAL EXCEPTION: main
09-01 18:36:05.584 E/AndroidRuntime(  925): Process: com.tencent.qqpimsecure, PID: 925
09-01 18:36:05.584 E/AndroidRuntime(  925): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at android.os.Looper.loop(Looper.java:164)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 18:36:05.584 E/AndroidRuntime(  925): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	... 8 more
09-01 18:36:05.584 E/AndroidRuntime(  925): Caused by: java.lang.reflect.UndeclaredThrowableException
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at $Proxy5.init(Unknown Source)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	... 12 more
09-01 18:36:05.584 E/AndroidRuntime(  925): Caused by: java.lang.reflect.InvocationTargetException
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	... 16 more
09-01 18:36:05.584 E/AndroidRuntime(  925): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{e9aeee7 u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at epetrp.b.c(SourceFile:8)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	at epetrp.c.init(SourceFile:1)
09-01 18:36:05.584 E/AndroidRuntime(  925): 	... 19 more
09-01 18:36:10.554 E/AndroidRuntime(  925): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-01 18:36:10.554 E/AndroidRuntime(  925): Process: com.tencent.qqpimsecure, PID: 925
09-01 18:36:10.554 E/AndroidRuntime(  925): java.lang.InternalError: Thread starting during runtime shutdown
09-01 18:36:10.554 E/AndroidRuntime(  925): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 18:36:10.554 E/AndroidRuntime(  925): 	at java.lang.Thread.start(Thread.java:733)
09-01 18:36:10.554 E/AndroidRuntime(  925): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 18:36:10.554 E/AndroidRuntime(  925): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 18:36:10.554 E/AndroidRuntime(  925): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 18:36:10.554 E/AndroidRuntime(  925): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 18:36:10.554 E/AndroidRuntime(  925): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 18:36:10.554 E/AndroidRuntime(  925): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 18:36:10.554 E/AndroidRuntime(  925): 	at tcs.bca.<init>(SourceFile:24)
09-01 18:36:10.554 E/AndroidRuntime(  925): 	at tcs.bcb.dv(SourceFile:157)
09-01 18:36:10.554 E/AndroidRuntime(  925): 	at tcs.bcb.b(SourceFile:135)
09-01 18:36:10.554 E/AndroidRuntime(  925): 	at tcs.bcb.uF(SourceFile:229)
09-01 18:36:10.554 E/AndroidRuntime(  925): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-01 18:36:10.554 E/AndroidRuntime(  925): 	at android.os.Handler.handleCallback(Handler.java:790)
09-01 18:36:10.554 E/AndroidRuntime(  925): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-01 18:36:10.554 E/AndroidRuntime(  925): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-01 18:36:10.554 E/AndroidRuntime(  925): 	at android.os.Looper.loop(Looper.java:164)
09-01 18:36:10.554 E/AndroidRuntime(  925): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 18:36:10.554 E/AndroidRuntime(  925): 	at tcs.alk.run(SourceFile:79)
09-01 18:36:10.590 E/AndroidRuntime(  925): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-01 18:36:10.590 E/AndroidRuntime(  925): Process: com.tencent.qqpimsecure, PID: 925
09-01 18:36:10.590 E/AndroidRuntime(  925): java.lang.reflect.UndeclaredThrowableException
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at $Proxy6.getPreferenceService(Unknown Source)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at epmt.j.c(SourceFile:1)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at epmt.c.a(SourceFile:2)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at epmt.g.l(SourceFile:99)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at epmt.g.a(SourceFile:2)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at epmt.g$c.handleMessage(SourceFile:1)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at android.os.Looper.loop(Looper.java:164)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at tcs.alk.run(SourceFile:79)
09-01 18:36:10.590 E/AndroidRuntime(  925): Caused by: java.lang.reflect.InvocationTargetException
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	... 10 more
09-01 18:36:10.590 E/AndroidRuntime(  925): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at java.lang.Thread.start(Thread.java:733)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at tcs.eiv.aq(SourceFile:111)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at tcs.ahr.<init>(SourceFile:16)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-01 18:36:10.590 E/AndroidRuntime(  925): 	... 13 more
09-01 18:36:12.424 E/AndroidRuntime( 1198): FATAL EXCEPTION: main
09-01 18:36:12.424 E/AndroidRuntime( 1198): Process: com.tencent.qqpimsecure, PID: 1198
09-01 18:36:12.424 E/AndroidRuntime( 1198): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at android.os.Looper.loop(Looper.java:164)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 18:36:12.424 E/AndroidRuntime( 1198): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	... 8 more
09-01 18:36:12.424 E/AndroidRuntime( 1198): Caused by: java.lang.reflect.UndeclaredThrowableException
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at $Proxy5.init(Unknown Source)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	... 12 more
09-01 18:36:12.424 E/AndroidRuntime( 1198): Caused by: java.lang.reflect.InvocationTargetException
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	... 16 more
09-01 18:36:12.424 E/AndroidRuntime( 1198): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{5b3cc14 u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at epetrp.b.c(SourceFile:8)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	at epetrp.c.init(SourceFile:1)
09-01 18:36:12.424 E/AndroidRuntime( 1198): 	... 19 more
09-01 18:36:17.405 E/AndroidRuntime( 1198): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-01 18:36:17.405 E/AndroidRuntime( 1198): Process: com.tencent.qqpimsecure, PID: 1198
09-01 18:36:17.405 E/AndroidRuntime( 1198): java.lang.InternalError: Thread starting during runtime shutdown
09-01 18:36:17.405 E/AndroidRuntime( 1198): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 18:36:17.405 E/AndroidRuntime( 1198): 	at java.lang.Thread.start(Thread.java:733)
09-01 18:36:17.405 E/AndroidRuntime( 1198): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 18:36:17.405 E/AndroidRuntime( 1198): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 18:36:17.405 E/AndroidRuntime( 1198): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 18:36:17.405 E/AndroidRuntime( 1198): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 18:36:17.405 E/AndroidRuntime( 1198): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 18:36:17.405 E/AndroidRuntime( 1198): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 18:36:17.405 E/AndroidRuntime( 1198): 	at tcs.bca.<init>(SourceFile:24)
09-01 18:36:17.405 E/AndroidRuntime( 1198): 	at tcs.bcb.dv(SourceFile:157)
09-01 18:36:17.405 E/AndroidRuntime( 1198): 	at tcs.bcb.b(SourceFile:135)
09-01 18:36:17.405 E/AndroidRuntime( 1198): 	at tcs.bcb.uF(SourceFile:229)
09-01 18:36:17.405 E/AndroidRuntime( 1198): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-01 18:36:17.405 E/AndroidRuntime( 1198): 	at android.os.Handler.handleCallback(Handler.java:790)
09-01 18:36:17.405 E/AndroidRuntime( 1198): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-01 18:36:17.405 E/AndroidRuntime( 1198): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-01 18:36:17.405 E/AndroidRuntime( 1198): 	at android.os.Looper.loop(Looper.java:164)
09-01 18:36:17.405 E/AndroidRuntime( 1198): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 18:36:17.405 E/AndroidRuntime( 1198): 	at tcs.alk.run(SourceFile:79)
09-01 18:36:17.429 E/AndroidRuntime( 1198): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-01 18:36:17.429 E/AndroidRuntime( 1198): Process: com.tencent.qqpimsecure, PID: 1198
09-01 18:36:17.429 E/AndroidRuntime( 1198): java.lang.reflect.UndeclaredThrowableException
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at $Proxy6.getPreferenceService(Unknown Source)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at epmt.j.c(SourceFile:1)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at epmt.c.a(SourceFile:2)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at epmt.g.l(SourceFile:99)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at epmt.g.a(SourceFile:2)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at epmt.g$c.handleMessage(SourceFile:1)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at android.os.Looper.loop(Looper.java:164)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at tcs.alk.run(SourceFile:79)
09-01 18:36:17.429 E/AndroidRuntime( 1198): Caused by: java.lang.reflect.InvocationTargetException
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	... 10 more
09-01 18:36:17.429 E/AndroidRuntime( 1198): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at java.lang.Thread.start(Thread.java:733)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at tcs.eiv.aq(SourceFile:111)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at tcs.ahr.<init>(SourceFile:16)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-01 18:36:17.429 E/AndroidRuntime( 1198): 	... 13 more
09-01 18:36:22.232 E/AndroidRuntime( 1452): FATAL EXCEPTION: main
09-01 18:36:22.232 E/AndroidRuntime( 1452): Process: com.tencent.qqpimsecure, PID: 1452
09-01 18:36:22.232 E/AndroidRuntime( 1452): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at android.os.Looper.loop(Looper.java:164)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 18:36:22.232 E/AndroidRuntime( 1452): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	... 8 more
09-01 18:36:22.232 E/AndroidRuntime( 1452): Caused by: java.lang.reflect.UndeclaredThrowableException
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at $Proxy5.init(Unknown Source)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	... 12 more
09-01 18:36:22.232 E/AndroidRuntime( 1452): Caused by: java.lang.reflect.InvocationTargetException
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	... 16 more
09-01 18:36:22.232 E/AndroidRuntime( 1452): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{ee60f41 u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at epetrp.b.c(SourceFile:8)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	at epetrp.c.init(SourceFile:1)
09-01 18:36:22.232 E/AndroidRuntime( 1452): 	... 19 more
09-01 18:36:27.214 E/AndroidRuntime( 1452): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-01 18:36:27.214 E/AndroidRuntime( 1452): Process: com.tencent.qqpimsecure, PID: 1452
09-01 18:36:27.214 E/AndroidRuntime( 1452): java.lang.InternalError: Thread starting during runtime shutdown
09-01 18:36:27.214 E/AndroidRuntime( 1452): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 18:36:27.214 E/AndroidRuntime( 1452): 	at java.lang.Thread.start(Thread.java:733)
09-01 18:36:27.214 E/AndroidRuntime( 1452): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 18:36:27.214 E/AndroidRuntime( 1452): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 18:36:27.214 E/AndroidRuntime( 1452): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 18:36:27.214 E/AndroidRuntime( 1452): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 18:36:27.214 E/AndroidRuntime( 1452): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 18:36:27.214 E/AndroidRuntime( 1452): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 18:36:27.214 E/AndroidRuntime( 1452): 	at tcs.bca.<init>(SourceFile:24)
09-01 18:36:27.214 E/AndroidRuntime( 1452): 	at tcs.bcb.dv(SourceFile:157)
09-01 18:36:27.214 E/AndroidRuntime( 1452): 	at tcs.bcb.b(SourceFile:135)
09-01 18:36:27.214 E/AndroidRuntime( 1452): 	at tcs.bcb.uF(SourceFile:229)
09-01 18:36:27.214 E/AndroidRuntime( 1452): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-01 18:36:27.214 E/AndroidRuntime( 1452): 	at android.os.Handler.handleCallback(Handler.java:790)
09-01 18:36:27.214 E/AndroidRuntime( 1452): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-01 18:36:27.214 E/AndroidRuntime( 1452): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-01 18:36:27.214 E/AndroidRuntime( 1452): 	at android.os.Looper.loop(Looper.java:164)
09-01 18:36:27.214 E/AndroidRuntime( 1452): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 18:36:27.214 E/AndroidRuntime( 1452): 	at tcs.alk.run(SourceFile:79)
09-01 18:36:27.237 E/AndroidRuntime( 1452): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-01 18:36:27.237 E/AndroidRuntime( 1452): Process: com.tencent.qqpimsecure, PID: 1452
09-01 18:36:27.237 E/AndroidRuntime( 1452): java.lang.reflect.UndeclaredThrowableException
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at $Proxy6.getPreferenceService(Unknown Source)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at epmt.j.c(SourceFile:1)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at epmt.c.a(SourceFile:2)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at epmt.g.l(SourceFile:99)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at epmt.g.a(SourceFile:2)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at epmt.g$c.handleMessage(SourceFile:1)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at android.os.Looper.loop(Looper.java:164)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at tcs.alk.run(SourceFile:79)
09-01 18:36:27.237 E/AndroidRuntime( 1452): Caused by: java.lang.reflect.InvocationTargetException
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	... 10 more
09-01 18:36:27.237 E/AndroidRuntime( 1452): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at java.lang.Thread.start(Thread.java:733)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at tcs.eiv.aq(SourceFile:111)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at tcs.ahr.<init>(SourceFile:16)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-01 18:36:27.237 E/AndroidRuntime( 1452): 	... 13 more
09-01 18:36:44.083 E/AndroidRuntime( 1773): FATAL EXCEPTION: main
09-01 18:36:44.083 E/AndroidRuntime( 1773): Process: com.tencent.qqpimsecure, PID: 1773
09-01 18:36:44.083 E/AndroidRuntime( 1773): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at android.os.Looper.loop(Looper.java:164)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 18:36:44.083 E/AndroidRuntime( 1773): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	... 8 more
09-01 18:36:44.083 E/AndroidRuntime( 1773): Caused by: java.lang.reflect.UndeclaredThrowableException
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at $Proxy5.init(Unknown Source)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	... 12 more
09-01 18:36:44.083 E/AndroidRuntime( 1773): Caused by: java.lang.reflect.InvocationTargetException
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	... 16 more
09-01 18:36:44.083 E/AndroidRuntime( 1773): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{9d901fd u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at epetrp.b.c(SourceFile:8)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	at epetrp.c.init(SourceFile:1)
09-01 18:36:44.083 E/AndroidRuntime( 1773): 	... 19 more
09-01 18:36:49.072 E/AndroidRuntime( 1773): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-01 18:36:49.072 E/AndroidRuntime( 1773): Process: com.tencent.qqpimsecure, PID: 1773
09-01 18:36:49.072 E/AndroidRuntime( 1773): java.lang.InternalError: Thread starting during runtime shutdown
09-01 18:36:49.072 E/AndroidRuntime( 1773): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 18:36:49.072 E/AndroidRuntime( 1773): 	at java.lang.Thread.start(Thread.java:733)
09-01 18:36:49.072 E/AndroidRuntime( 1773): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 18:36:49.072 E/AndroidRuntime( 1773): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 18:36:49.072 E/AndroidRuntime( 1773): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 18:36:49.072 E/AndroidRuntime( 1773): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 18:36:49.072 E/AndroidRuntime( 1773): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 18:36:49.072 E/AndroidRuntime( 1773): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 18:36:49.072 E/AndroidRuntime( 1773): 	at tcs.bca.<init>(SourceFile:24)
09-01 18:36:49.072 E/AndroidRuntime( 1773): 	at tcs.bcb.dv(SourceFile:157)
09-01 18:36:49.072 E/AndroidRuntime( 1773): 	at tcs.bcb.b(SourceFile:135)
09-01 18:36:49.072 E/AndroidRuntime( 1773): 	at tcs.bcb.uF(SourceFile:229)
09-01 18:36:49.072 E/AndroidRuntime( 1773): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-01 18:36:49.072 E/AndroidRuntime( 1773): 	at android.os.Handler.handleCallback(Handler.java:790)
09-01 18:36:49.072 E/AndroidRuntime( 1773): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-01 18:36:49.072 E/AndroidRuntime( 1773): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-01 18:36:49.072 E/AndroidRuntime( 1773): 	at android.os.Looper.loop(Looper.java:164)
09-01 18:36:49.072 E/AndroidRuntime( 1773): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 18:36:49.072 E/AndroidRuntime( 1773): 	at tcs.alk.run(SourceFile:79)
09-01 18:36:49.088 E/AndroidRuntime( 1773): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-01 18:36:49.088 E/AndroidRuntime( 1773): Process: com.tencent.qqpimsecure, PID: 1773
09-01 18:36:49.088 E/AndroidRuntime( 1773): java.lang.reflect.UndeclaredThrowableException
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at $Proxy6.getPreferenceService(Unknown Source)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at epmt.j.c(SourceFile:1)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at epmt.c.a(SourceFile:2)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at epmt.g.l(SourceFile:99)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at epmt.g.a(SourceFile:2)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at epmt.g$c.handleMessage(SourceFile:1)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at android.os.Looper.loop(Looper.java:164)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at tcs.alk.run(SourceFile:79)
09-01 18:36:49.088 E/AndroidRuntime( 1773): Caused by: java.lang.reflect.InvocationTargetException
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	... 10 more
09-01 18:36:49.088 E/AndroidRuntime( 1773): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at java.lang.Thread.start(Thread.java:733)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at tcs.eiv.aq(SourceFile:111)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at tcs.ahr.<init>(SourceFile:16)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-01 18:36:49.088 E/AndroidRuntime( 1773): 	... 13 more
09-01 18:37:53.963 E/AndroidRuntime( 2074): FATAL EXCEPTION: main
09-01 18:37:53.963 E/AndroidRuntime( 2074): Process: com.tencent.qqpimsecure, PID: 2074
09-01 18:37:53.963 E/AndroidRuntime( 2074): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at android.os.Looper.loop(Looper.java:164)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 18:37:53.963 E/AndroidRuntime( 2074): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	... 8 more
09-01 18:37:53.963 E/AndroidRuntime( 2074): Caused by: java.lang.reflect.UndeclaredThrowableException
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at $Proxy5.init(Unknown Source)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	... 12 more
09-01 18:37:53.963 E/AndroidRuntime( 2074): Caused by: java.lang.reflect.InvocationTargetException
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	... 16 more
09-01 18:37:53.963 E/AndroidRuntime( 2074): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{90ef1df u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at epetrp.b.c(SourceFile:8)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	at epetrp.c.init(SourceFile:1)
09-01 18:37:53.963 E/AndroidRuntime( 2074): 	... 19 more
09-01 18:37:58.949 E/AndroidRuntime( 2074): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-01 18:37:58.949 E/AndroidRuntime( 2074): Process: com.tencent.qqpimsecure, PID: 2074
09-01 18:37:58.949 E/AndroidRuntime( 2074): java.lang.InternalError: Thread starting during runtime shutdown
09-01 18:37:58.949 E/AndroidRuntime( 2074): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 18:37:58.949 E/AndroidRuntime( 2074): 	at java.lang.Thread.start(Thread.java:733)
09-01 18:37:58.949 E/AndroidRuntime( 2074): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 18:37:58.949 E/AndroidRuntime( 2074): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 18:37:58.949 E/AndroidRuntime( 2074): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 18:37:58.949 E/AndroidRuntime( 2074): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 18:37:58.949 E/AndroidRuntime( 2074): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 18:37:58.949 E/AndroidRuntime( 2074): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 18:37:58.949 E/AndroidRuntime( 2074): 	at tcs.bca.<init>(SourceFile:24)
09-01 18:37:58.949 E/AndroidRuntime( 2074): 	at tcs.bcb.dv(SourceFile:157)
09-01 18:37:58.949 E/AndroidRuntime( 2074): 	at tcs.bcb.b(SourceFile:135)
09-01 18:37:58.949 E/AndroidRuntime( 2074): 	at tcs.bcb.uF(SourceFile:229)
09-01 18:37:58.949 E/AndroidRuntime( 2074): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-01 18:37:58.949 E/AndroidRuntime( 2074): 	at android.os.Handler.handleCallback(Handler.java:790)
09-01 18:37:58.949 E/AndroidRuntime( 2074): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-01 18:37:58.949 E/AndroidRuntime( 2074): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-01 18:37:58.949 E/AndroidRuntime( 2074): 	at android.os.Looper.loop(Looper.java:164)
09-01 18:37:58.949 E/AndroidRuntime( 2074): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 18:37:58.949 E/AndroidRuntime( 2074): 	at tcs.alk.run(SourceFile:79)
09-01 18:37:58.967 E/AndroidRuntime( 2074): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-01 18:37:58.967 E/AndroidRuntime( 2074): Process: com.tencent.qqpimsecure, PID: 2074
09-01 18:37:58.967 E/AndroidRuntime( 2074): java.lang.reflect.UndeclaredThrowableException
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at $Proxy6.getPreferenceService(Unknown Source)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at epmt.j.c(SourceFile:1)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at epmt.c.a(SourceFile:2)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at epmt.g.l(SourceFile:99)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at epmt.g.a(SourceFile:2)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at epmt.g$c.handleMessage(SourceFile:1)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at android.os.Looper.loop(Looper.java:164)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at tcs.alk.run(SourceFile:79)
09-01 18:37:58.967 E/AndroidRuntime( 2074): Caused by: java.lang.reflect.InvocationTargetException
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	... 10 more
09-01 18:37:58.967 E/AndroidRuntime( 2074): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at java.lang.Thread.start(Thread.java:733)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at tcs.eiv.aq(SourceFile:111)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at tcs.ahr.<init>(SourceFile:16)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-01 18:37:58.967 E/AndroidRuntime( 2074): 	... 13 more
09-01 23:36:05.370 E/AndroidRuntime( 1944): FATAL EXCEPTION: main
09-01 23:36:05.370 E/AndroidRuntime( 1944): Process: com.tencent.qqpimsecure, PID: 1944
09-01 23:36:05.370 E/AndroidRuntime( 1944): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at android.os.Looper.loop(Looper.java:164)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 23:36:05.370 E/AndroidRuntime( 1944): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	... 8 more
09-01 23:36:05.370 E/AndroidRuntime( 1944): Caused by: java.lang.reflect.UndeclaredThrowableException
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at $Proxy5.init(Unknown Source)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	... 12 more
09-01 23:36:05.370 E/AndroidRuntime( 1944): Caused by: java.lang.reflect.InvocationTargetException
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	... 16 more
09-01 23:36:05.370 E/AndroidRuntime( 1944): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{4fc71a7 u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at epetrp.b.c(SourceFile:8)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	at epetrp.c.init(SourceFile:1)
09-01 23:36:05.370 E/AndroidRuntime( 1944): 	... 19 more
09-01 23:36:10.345 E/AndroidRuntime( 1944): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-01 23:36:10.345 E/AndroidRuntime( 1944): Process: com.tencent.qqpimsecure, PID: 1944
09-01 23:36:10.345 E/AndroidRuntime( 1944): java.lang.InternalError: Thread starting during runtime shutdown
09-01 23:36:10.345 E/AndroidRuntime( 1944): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 23:36:10.345 E/AndroidRuntime( 1944): 	at java.lang.Thread.start(Thread.java:733)
09-01 23:36:10.345 E/AndroidRuntime( 1944): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 23:36:10.345 E/AndroidRuntime( 1944): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 23:36:10.345 E/AndroidRuntime( 1944): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 23:36:10.345 E/AndroidRuntime( 1944): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 23:36:10.345 E/AndroidRuntime( 1944): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 23:36:10.345 E/AndroidRuntime( 1944): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 23:36:10.345 E/AndroidRuntime( 1944): 	at tcs.bca.<init>(SourceFile:24)
09-01 23:36:10.345 E/AndroidRuntime( 1944): 	at tcs.bcb.dv(SourceFile:157)
09-01 23:36:10.345 E/AndroidRuntime( 1944): 	at tcs.bcb.b(SourceFile:135)
09-01 23:36:10.345 E/AndroidRuntime( 1944): 	at tcs.bcb.uF(SourceFile:229)
09-01 23:36:10.345 E/AndroidRuntime( 1944): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-01 23:36:10.345 E/AndroidRuntime( 1944): 	at android.os.Handler.handleCallback(Handler.java:790)
09-01 23:36:10.345 E/AndroidRuntime( 1944): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-01 23:36:10.345 E/AndroidRuntime( 1944): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-01 23:36:10.345 E/AndroidRuntime( 1944): 	at android.os.Looper.loop(Looper.java:164)
09-01 23:36:10.345 E/AndroidRuntime( 1944): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 23:36:10.345 E/AndroidRuntime( 1944): 	at tcs.alk.run(SourceFile:79)
09-01 23:36:10.374 E/AndroidRuntime( 1944): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-01 23:36:10.374 E/AndroidRuntime( 1944): Process: com.tencent.qqpimsecure, PID: 1944
09-01 23:36:10.374 E/AndroidRuntime( 1944): java.lang.reflect.UndeclaredThrowableException
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at $Proxy6.getPreferenceService(Unknown Source)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at epmt.j.c(SourceFile:1)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at epmt.c.a(SourceFile:2)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at epmt.g.l(SourceFile:99)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at epmt.g.a(SourceFile:2)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at epmt.g$c.handleMessage(SourceFile:1)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at android.os.Looper.loop(Looper.java:164)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at tcs.alk.run(SourceFile:79)
09-01 23:36:10.374 E/AndroidRuntime( 1944): Caused by: java.lang.reflect.InvocationTargetException
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	... 10 more
09-01 23:36:10.374 E/AndroidRuntime( 1944): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at java.lang.Thread.start(Thread.java:733)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at tcs.eiv.aq(SourceFile:111)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at tcs.ahr.<init>(SourceFile:16)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-01 23:36:10.374 E/AndroidRuntime( 1944): 	... 13 more
09-01 23:36:12.133 E/AndroidRuntime( 2251): FATAL EXCEPTION: main
09-01 23:36:12.133 E/AndroidRuntime( 2251): Process: com.tencent.qqpimsecure, PID: 2251
09-01 23:36:12.133 E/AndroidRuntime( 2251): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at android.os.Looper.loop(Looper.java:164)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 23:36:12.133 E/AndroidRuntime( 2251): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	... 8 more
09-01 23:36:12.133 E/AndroidRuntime( 2251): Caused by: java.lang.reflect.UndeclaredThrowableException
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at $Proxy5.init(Unknown Source)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	... 12 more
09-01 23:36:12.133 E/AndroidRuntime( 2251): Caused by: java.lang.reflect.InvocationTargetException
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	... 16 more
09-01 23:36:12.133 E/AndroidRuntime( 2251): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{804ed1 u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at epetrp.b.c(SourceFile:8)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	at epetrp.c.init(SourceFile:1)
09-01 23:36:12.133 E/AndroidRuntime( 2251): 	... 19 more
09-01 23:36:17.122 E/AndroidRuntime( 2251): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-01 23:36:17.122 E/AndroidRuntime( 2251): Process: com.tencent.qqpimsecure, PID: 2251
09-01 23:36:17.122 E/AndroidRuntime( 2251): java.lang.InternalError: Thread starting during runtime shutdown
09-01 23:36:17.122 E/AndroidRuntime( 2251): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 23:36:17.122 E/AndroidRuntime( 2251): 	at java.lang.Thread.start(Thread.java:733)
09-01 23:36:17.122 E/AndroidRuntime( 2251): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 23:36:17.122 E/AndroidRuntime( 2251): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 23:36:17.122 E/AndroidRuntime( 2251): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 23:36:17.122 E/AndroidRuntime( 2251): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 23:36:17.122 E/AndroidRuntime( 2251): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 23:36:17.122 E/AndroidRuntime( 2251): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 23:36:17.122 E/AndroidRuntime( 2251): 	at tcs.bca.<init>(SourceFile:24)
09-01 23:36:17.122 E/AndroidRuntime( 2251): 	at tcs.bcb.dv(SourceFile:157)
09-01 23:36:17.122 E/AndroidRuntime( 2251): 	at tcs.bcb.b(SourceFile:135)
09-01 23:36:17.122 E/AndroidRuntime( 2251): 	at tcs.bcb.uF(SourceFile:229)
09-01 23:36:17.122 E/AndroidRuntime( 2251): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-01 23:36:17.122 E/AndroidRuntime( 2251): 	at android.os.Handler.handleCallback(Handler.java:790)
09-01 23:36:17.122 E/AndroidRuntime( 2251): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-01 23:36:17.122 E/AndroidRuntime( 2251): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-01 23:36:17.122 E/AndroidRuntime( 2251): 	at android.os.Looper.loop(Looper.java:164)
09-01 23:36:17.122 E/AndroidRuntime( 2251): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 23:36:17.122 E/AndroidRuntime( 2251): 	at tcs.alk.run(SourceFile:79)
09-01 23:36:17.140 E/AndroidRuntime( 2251): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-01 23:36:17.140 E/AndroidRuntime( 2251): Process: com.tencent.qqpimsecure, PID: 2251
09-01 23:36:17.140 E/AndroidRuntime( 2251): java.lang.reflect.UndeclaredThrowableException
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at $Proxy6.getPreferenceService(Unknown Source)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at epmt.j.c(SourceFile:1)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at epmt.c.a(SourceFile:2)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at epmt.g.l(SourceFile:99)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at epmt.g.a(SourceFile:2)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at epmt.g$c.handleMessage(SourceFile:1)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at android.os.Looper.loop(Looper.java:164)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at tcs.alk.run(SourceFile:79)
09-01 23:36:17.140 E/AndroidRuntime( 2251): Caused by: java.lang.reflect.InvocationTargetException
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	... 10 more
09-01 23:36:17.140 E/AndroidRuntime( 2251): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at java.lang.Thread.start(Thread.java:733)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at tcs.eiv.aq(SourceFile:111)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at tcs.ahr.<init>(SourceFile:16)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-01 23:36:17.140 E/AndroidRuntime( 2251): 	... 13 more
09-01 23:36:22.018 E/AndroidRuntime( 2454): FATAL EXCEPTION: main
09-01 23:36:22.018 E/AndroidRuntime( 2454): Process: com.tencent.qqpimsecure, PID: 2454
09-01 23:36:22.018 E/AndroidRuntime( 2454): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at android.os.Looper.loop(Looper.java:164)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 23:36:22.018 E/AndroidRuntime( 2454): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	... 8 more
09-01 23:36:22.018 E/AndroidRuntime( 2454): Caused by: java.lang.reflect.UndeclaredThrowableException
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at $Proxy5.init(Unknown Source)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	... 12 more
09-01 23:36:22.018 E/AndroidRuntime( 2454): Caused by: java.lang.reflect.InvocationTargetException
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	... 16 more
09-01 23:36:22.018 E/AndroidRuntime( 2454): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{98e1894 u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at epetrp.b.c(SourceFile:8)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	at epetrp.c.init(SourceFile:1)
09-01 23:36:22.018 E/AndroidRuntime( 2454): 	... 19 more
09-01 23:36:27.007 E/AndroidRuntime( 2454): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-01 23:36:27.007 E/AndroidRuntime( 2454): Process: com.tencent.qqpimsecure, PID: 2454
09-01 23:36:27.007 E/AndroidRuntime( 2454): java.lang.InternalError: Thread starting during runtime shutdown
09-01 23:36:27.007 E/AndroidRuntime( 2454): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 23:36:27.007 E/AndroidRuntime( 2454): 	at java.lang.Thread.start(Thread.java:733)
09-01 23:36:27.007 E/AndroidRuntime( 2454): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 23:36:27.007 E/AndroidRuntime( 2454): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 23:36:27.007 E/AndroidRuntime( 2454): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 23:36:27.007 E/AndroidRuntime( 2454): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 23:36:27.007 E/AndroidRuntime( 2454): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 23:36:27.007 E/AndroidRuntime( 2454): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 23:36:27.007 E/AndroidRuntime( 2454): 	at tcs.bca.<init>(SourceFile:24)
09-01 23:36:27.007 E/AndroidRuntime( 2454): 	at tcs.bcb.dv(SourceFile:157)
09-01 23:36:27.007 E/AndroidRuntime( 2454): 	at tcs.bcb.b(SourceFile:135)
09-01 23:36:27.007 E/AndroidRuntime( 2454): 	at tcs.bcb.uF(SourceFile:229)
09-01 23:36:27.007 E/AndroidRuntime( 2454): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-01 23:36:27.007 E/AndroidRuntime( 2454): 	at android.os.Handler.handleCallback(Handler.java:790)
09-01 23:36:27.007 E/AndroidRuntime( 2454): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-01 23:36:27.007 E/AndroidRuntime( 2454): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-01 23:36:27.007 E/AndroidRuntime( 2454): 	at android.os.Looper.loop(Looper.java:164)
09-01 23:36:27.007 E/AndroidRuntime( 2454): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 23:36:27.007 E/AndroidRuntime( 2454): 	at tcs.alk.run(SourceFile:79)
09-01 23:36:27.031 E/AndroidRuntime( 2454): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-01 23:36:27.031 E/AndroidRuntime( 2454): Process: com.tencent.qqpimsecure, PID: 2454
09-01 23:36:27.031 E/AndroidRuntime( 2454): java.lang.reflect.UndeclaredThrowableException
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at $Proxy6.getPreferenceService(Unknown Source)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at epmt.j.c(SourceFile:1)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at epmt.c.a(SourceFile:2)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at epmt.g.l(SourceFile:99)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at epmt.g.a(SourceFile:2)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at epmt.g$c.handleMessage(SourceFile:1)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at android.os.Looper.loop(Looper.java:164)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at tcs.alk.run(SourceFile:79)
09-01 23:36:27.031 E/AndroidRuntime( 2454): Caused by: java.lang.reflect.InvocationTargetException
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	... 10 more
09-01 23:36:27.031 E/AndroidRuntime( 2454): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at java.lang.Thread.start(Thread.java:733)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at tcs.eiv.aq(SourceFile:111)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at tcs.ahr.<init>(SourceFile:16)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-01 23:36:27.031 E/AndroidRuntime( 2454): 	... 13 more
09-01 23:36:43.890 E/AndroidRuntime( 2706): FATAL EXCEPTION: main
09-01 23:36:43.890 E/AndroidRuntime( 2706): Process: com.tencent.qqpimsecure, PID: 2706
09-01 23:36:43.890 E/AndroidRuntime( 2706): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at android.os.Looper.loop(Looper.java:164)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 23:36:43.890 E/AndroidRuntime( 2706): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	... 8 more
09-01 23:36:43.890 E/AndroidRuntime( 2706): Caused by: java.lang.reflect.UndeclaredThrowableException
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at $Proxy6.init(Unknown Source)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	... 12 more
09-01 23:36:43.890 E/AndroidRuntime( 2706): Caused by: java.lang.reflect.InvocationTargetException
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	... 16 more
09-01 23:36:43.890 E/AndroidRuntime( 2706): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{9a9f9c1 u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at epetrp.b.c(SourceFile:8)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	at epetrp.c.init(SourceFile:1)
09-01 23:36:43.890 E/AndroidRuntime( 2706): 	... 19 more
09-01 23:36:48.869 E/AndroidRuntime( 2706): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-01 23:36:48.869 E/AndroidRuntime( 2706): Process: com.tencent.qqpimsecure, PID: 2706
09-01 23:36:48.869 E/AndroidRuntime( 2706): java.lang.InternalError: Thread starting during runtime shutdown
09-01 23:36:48.869 E/AndroidRuntime( 2706): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 23:36:48.869 E/AndroidRuntime( 2706): 	at java.lang.Thread.start(Thread.java:733)
09-01 23:36:48.869 E/AndroidRuntime( 2706): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 23:36:48.869 E/AndroidRuntime( 2706): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 23:36:48.869 E/AndroidRuntime( 2706): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 23:36:48.869 E/AndroidRuntime( 2706): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 23:36:48.869 E/AndroidRuntime( 2706): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 23:36:48.869 E/AndroidRuntime( 2706): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 23:36:48.869 E/AndroidRuntime( 2706): 	at tcs.bca.<init>(SourceFile:24)
09-01 23:36:48.869 E/AndroidRuntime( 2706): 	at tcs.bcb.dv(SourceFile:157)
09-01 23:36:48.869 E/AndroidRuntime( 2706): 	at tcs.bcb.b(SourceFile:135)
09-01 23:36:48.869 E/AndroidRuntime( 2706): 	at tcs.bcb.uF(SourceFile:229)
09-01 23:36:48.869 E/AndroidRuntime( 2706): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-01 23:36:48.869 E/AndroidRuntime( 2706): 	at android.os.Handler.handleCallback(Handler.java:790)
09-01 23:36:48.869 E/AndroidRuntime( 2706): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-01 23:36:48.869 E/AndroidRuntime( 2706): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-01 23:36:48.869 E/AndroidRuntime( 2706): 	at android.os.Looper.loop(Looper.java:164)
09-01 23:36:48.869 E/AndroidRuntime( 2706): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 23:36:48.869 E/AndroidRuntime( 2706): 	at tcs.alk.run(SourceFile:79)
09-01 23:36:48.894 E/AndroidRuntime( 2706): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-01 23:36:48.894 E/AndroidRuntime( 2706): Process: com.tencent.qqpimsecure, PID: 2706
09-01 23:36:48.894 E/AndroidRuntime( 2706): java.lang.reflect.UndeclaredThrowableException
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at $Proxy5.getPreferenceService(Unknown Source)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at epmt.j.c(SourceFile:1)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at epmt.c.a(SourceFile:2)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at epmt.g.l(SourceFile:99)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at epmt.g.a(SourceFile:2)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at epmt.g$c.handleMessage(SourceFile:1)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at android.os.Looper.loop(Looper.java:164)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at tcs.alk.run(SourceFile:79)
09-01 23:36:48.894 E/AndroidRuntime( 2706): Caused by: java.lang.reflect.InvocationTargetException
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	... 10 more
09-01 23:36:48.894 E/AndroidRuntime( 2706): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at java.lang.Thread.start(Thread.java:733)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at tcs.eiv.aq(SourceFile:111)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at tcs.ahr.<init>(SourceFile:16)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-01 23:36:48.894 E/AndroidRuntime( 2706): 	... 13 more
09-01 23:37:53.764 E/AndroidRuntime( 3007): FATAL EXCEPTION: main
09-01 23:37:53.764 E/AndroidRuntime( 3007): Process: com.tencent.qqpimsecure, PID: 3007
09-01 23:37:53.764 E/AndroidRuntime( 3007): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at android.os.Looper.loop(Looper.java:164)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-01 23:37:53.764 E/AndroidRuntime( 3007): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	... 8 more
09-01 23:37:53.764 E/AndroidRuntime( 3007): Caused by: java.lang.reflect.UndeclaredThrowableException
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at $Proxy5.init(Unknown Source)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	... 12 more
09-01 23:37:53.764 E/AndroidRuntime( 3007): Caused by: java.lang.reflect.InvocationTargetException
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	... 16 more
09-01 23:37:53.764 E/AndroidRuntime( 3007): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{ac9802e u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at epetrp.b.c(SourceFile:8)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	at epetrp.c.init(SourceFile:1)
09-01 23:37:53.764 E/AndroidRuntime( 3007): 	... 19 more
09-01 23:37:58.740 E/AndroidRuntime( 3007): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-01 23:37:58.740 E/AndroidRuntime( 3007): Process: com.tencent.qqpimsecure, PID: 3007
09-01 23:37:58.740 E/AndroidRuntime( 3007): java.lang.InternalError: Thread starting during runtime shutdown
09-01 23:37:58.740 E/AndroidRuntime( 3007): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 23:37:58.740 E/AndroidRuntime( 3007): 	at java.lang.Thread.start(Thread.java:733)
09-01 23:37:58.740 E/AndroidRuntime( 3007): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 23:37:58.740 E/AndroidRuntime( 3007): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 23:37:58.740 E/AndroidRuntime( 3007): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 23:37:58.740 E/AndroidRuntime( 3007): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 23:37:58.740 E/AndroidRuntime( 3007): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 23:37:58.740 E/AndroidRuntime( 3007): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 23:37:58.740 E/AndroidRuntime( 3007): 	at tcs.bca.<init>(SourceFile:24)
09-01 23:37:58.740 E/AndroidRuntime( 3007): 	at tcs.bcb.dv(SourceFile:157)
09-01 23:37:58.740 E/AndroidRuntime( 3007): 	at tcs.bcb.b(SourceFile:135)
09-01 23:37:58.740 E/AndroidRuntime( 3007): 	at tcs.bcb.uF(SourceFile:229)
09-01 23:37:58.740 E/AndroidRuntime( 3007): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-01 23:37:58.740 E/AndroidRuntime( 3007): 	at android.os.Handler.handleCallback(Handler.java:790)
09-01 23:37:58.740 E/AndroidRuntime( 3007): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-01 23:37:58.740 E/AndroidRuntime( 3007): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-01 23:37:58.740 E/AndroidRuntime( 3007): 	at android.os.Looper.loop(Looper.java:164)
09-01 23:37:58.740 E/AndroidRuntime( 3007): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 23:37:58.740 E/AndroidRuntime( 3007): 	at tcs.alk.run(SourceFile:79)
09-01 23:37:58.767 E/AndroidRuntime( 3007): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-01 23:37:58.767 E/AndroidRuntime( 3007): Process: com.tencent.qqpimsecure, PID: 3007
09-01 23:37:58.767 E/AndroidRuntime( 3007): java.lang.reflect.UndeclaredThrowableException
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at $Proxy6.getPreferenceService(Unknown Source)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at epmt.j.c(SourceFile:1)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at epmt.c.a(SourceFile:2)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at epmt.g.l(SourceFile:99)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at epmt.g.a(SourceFile:2)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at epmt.g$c.handleMessage(SourceFile:1)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at android.os.Looper.loop(Looper.java:164)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at tcs.alk.run(SourceFile:79)
09-01 23:37:58.767 E/AndroidRuntime( 3007): Caused by: java.lang.reflect.InvocationTargetException
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at java.lang.reflect.Method.invoke(Native Method)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	... 10 more
09-01 23:37:58.767 E/AndroidRuntime( 3007): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at java.lang.Thread.nativeCreate(Native Method)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at java.lang.Thread.start(Thread.java:733)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at tcs.eiv.aq(SourceFile:111)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at tcs.ahr.<init>(SourceFile:16)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-01 23:37:58.767 E/AndroidRuntime( 3007): 	... 13 more
09-02 00:00:37.004 E/ActivityThread( 3253): Failed to find provider info for com.android.badge
09-02 00:00:37.037 E/ActivityThread( 3253): Failed to find provider info for com.android.badge
09-02 03:08:08.065 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher2.permission.READ_SETTINGS in package: com.tencent.mobileqq at: Binary XML file line #83
09-02 03:08:08.068 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WRITE_CONTACTS in package: com.tencent.mobileqq at: Binary XML file line #114
09-02 03:08:08.074 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #185
09-02 03:08:08.074 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CHANGE_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #192
09-02 03:08:08.074 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.INTERNET in package: com.tencent.mobileqq at: Binary XML file line #193
09-02 03:08:08.074 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #194
09-02 03:08:08.075 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_NETWORK_STATE in package: com.tencent.mobileqq at: Binary XML file line #195
09-02 03:08:08.075 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CAMERA in package: com.tencent.mobileqq at: Binary XML file line #199
09-02 03:08:08.075 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.tencent.mobileqq at: Binary XML file line #200
09-02 03:08:08.075 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WAKE_LOCK in package: com.tencent.mobileqq at: Binary XML file line #201
09-02 03:08:08.075 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher.permission.INSTALL_SHORTCUT in package: com.tencent.mobileqq at: Binary XML file line #202
09-02 03:08:08.075 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.RECEIVE_BOOT_COMPLETED in package: com.tencent.mobileqq at: Binary XML file line #203
09-02 03:08:08.075 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #205
09-02 03:08:08.087 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Android/data/com.tencent.mobileqq/Tencent/TMAssistantSDK/Download/com.tencent.mobileqq/AndroidBBPJQQ_8.8.17.5770_537084958_bbb5f11ab5cf828c12abf84c5b33db55.apk Binary XML file line #2062
09-02 03:08:10.893 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.qqpimsecure-6755.apk Binary XML file line #836
09-02 03:08:11.175 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.sohu.inputmethod.sogou1460.apk Binary XML file line #264
09-02 03:08:11.258 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.qqpimsecure-6790.apk Binary XML file line #834
09-02 03:08:11.399 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher2.permission.READ_SETTINGS in package: com.tencent.mobileqq at: Binary XML file line #81
09-02 03:08:11.400 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WRITE_CONTACTS in package: com.tencent.mobileqq at: Binary XML file line #112
09-02 03:08:11.407 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #183
09-02 03:08:11.407 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CHANGE_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #190
09-02 03:08:11.407 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.INTERNET in package: com.tencent.mobileqq at: Binary XML file line #191
09-02 03:08:11.407 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #192
09-02 03:08:11.407 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_NETWORK_STATE in package: com.tencent.mobileqq at: Binary XML file line #193
09-02 03:08:11.407 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CAMERA in package: com.tencent.mobileqq at: Binary XML file line #197
09-02 03:08:11.407 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.tencent.mobileqq at: Binary XML file line #198
09-02 03:08:11.407 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WAKE_LOCK in package: com.tencent.mobileqq at: Binary XML file line #199
09-02 03:08:11.407 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher.permission.INSTALL_SHORTCUT in package: com.tencent.mobileqq at: Binary XML file line #200
09-02 03:08:11.407 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.RECEIVE_BOOT_COMPLETED in package: com.tencent.mobileqq at: Binary XML file line #201
09-02 03:08:11.407 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #203
09-02 03:08:11.417 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.mobileqq1792.apk Binary XML file line #2077
09-02 03:08:11.531 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-02 03:08:11.532 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/WeiXin/yunting-pugongying-debug.apk Binary XML file line #74
09-02 03:08:11.542 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/WeiXin/yunting-pugongying-debug.apk Binary XML file line #1330
09-02 03:08:11.570 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-02 03:08:11.571 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/??????_6.32.0.8340.apk Binary XML file line #74
09-02 03:08:11.579 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/??????_6.32.0.8340.apk Binary XML file line #1319
09-02 03:08:11.593 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-02 03:08:11.594 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/??????_6.32.0.8340-1.apk Binary XML file line #74
09-02 03:08:11.602 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/??????_6.32.0.8340-1.apk Binary XML file line #1319
09-02 03:08:13.687 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-02 03:08:13.689 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/download/WeiXin/yunting-pugongying-debug.apk Binary XML file line #74
09-02 03:08:13.698 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/download/WeiXin/yunting-pugongying-debug.apk Binary XML file line #1330
09-02 03:08:13.713 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-02 03:08:13.714 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/download/??????_6.32.0.8340.apk Binary XML file line #74
09-02 03:08:13.723 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/download/??????_6.32.0.8340.apk Binary XML file line #1319
09-02 03:08:13.737 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-02 03:08:13.738 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/download/??????_6.32.0.8340-1.apk Binary XML file line #74
09-02 03:08:13.747 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/download/??????_6.32.0.8340-1.apk Binary XML file line #1319
09-02 04:36:05.597 E/AndroidRuntime( 2228): FATAL EXCEPTION: main
09-02 04:36:05.597 E/AndroidRuntime( 2228): Process: com.tencent.qqpimsecure, PID: 2228
09-02 04:36:05.597 E/AndroidRuntime( 2228): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at android.os.Looper.loop(Looper.java:164)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 04:36:05.597 E/AndroidRuntime( 2228): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	... 8 more
09-02 04:36:05.597 E/AndroidRuntime( 2228): Caused by: java.lang.reflect.UndeclaredThrowableException
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at $Proxy5.init(Unknown Source)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	... 12 more
09-02 04:36:05.597 E/AndroidRuntime( 2228): Caused by: java.lang.reflect.InvocationTargetException
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	... 16 more
09-02 04:36:05.597 E/AndroidRuntime( 2228): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{5b03cee u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at epetrp.b.c(SourceFile:8)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	at epetrp.c.init(SourceFile:1)
09-02 04:36:05.597 E/AndroidRuntime( 2228): 	... 19 more
09-02 04:36:10.569 E/AndroidRuntime( 2228): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-02 04:36:10.569 E/AndroidRuntime( 2228): Process: com.tencent.qqpimsecure, PID: 2228
09-02 04:36:10.569 E/AndroidRuntime( 2228): java.lang.InternalError: Thread starting during runtime shutdown
09-02 04:36:10.569 E/AndroidRuntime( 2228): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 04:36:10.569 E/AndroidRuntime( 2228): 	at java.lang.Thread.start(Thread.java:733)
09-02 04:36:10.569 E/AndroidRuntime( 2228): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 04:36:10.569 E/AndroidRuntime( 2228): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 04:36:10.569 E/AndroidRuntime( 2228): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 04:36:10.569 E/AndroidRuntime( 2228): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 04:36:10.569 E/AndroidRuntime( 2228): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 04:36:10.569 E/AndroidRuntime( 2228): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 04:36:10.569 E/AndroidRuntime( 2228): 	at tcs.bca.<init>(SourceFile:24)
09-02 04:36:10.569 E/AndroidRuntime( 2228): 	at tcs.bcb.dv(SourceFile:157)
09-02 04:36:10.569 E/AndroidRuntime( 2228): 	at tcs.bcb.b(SourceFile:135)
09-02 04:36:10.569 E/AndroidRuntime( 2228): 	at tcs.bcb.uF(SourceFile:229)
09-02 04:36:10.569 E/AndroidRuntime( 2228): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-02 04:36:10.569 E/AndroidRuntime( 2228): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 04:36:10.569 E/AndroidRuntime( 2228): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 04:36:10.569 E/AndroidRuntime( 2228): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-02 04:36:10.569 E/AndroidRuntime( 2228): 	at android.os.Looper.loop(Looper.java:164)
09-02 04:36:10.569 E/AndroidRuntime( 2228): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 04:36:10.569 E/AndroidRuntime( 2228): 	at tcs.alk.run(SourceFile:79)
09-02 04:36:10.599 E/AndroidRuntime( 2228): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-02 04:36:10.599 E/AndroidRuntime( 2228): Process: com.tencent.qqpimsecure, PID: 2228
09-02 04:36:10.599 E/AndroidRuntime( 2228): java.lang.reflect.UndeclaredThrowableException
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at $Proxy6.getPreferenceService(Unknown Source)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at epmt.j.c(SourceFile:1)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at epmt.c.a(SourceFile:2)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at epmt.g.l(SourceFile:99)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at epmt.g.a(SourceFile:2)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at epmt.g$c.handleMessage(SourceFile:1)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at android.os.Looper.loop(Looper.java:164)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at tcs.alk.run(SourceFile:79)
09-02 04:36:10.599 E/AndroidRuntime( 2228): Caused by: java.lang.reflect.InvocationTargetException
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	... 10 more
09-02 04:36:10.599 E/AndroidRuntime( 2228): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at java.lang.Thread.start(Thread.java:733)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at tcs.eiv.aq(SourceFile:111)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at tcs.ahr.<init>(SourceFile:16)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-02 04:36:10.599 E/AndroidRuntime( 2228): 	... 13 more
09-02 04:36:12.526 E/AndroidRuntime( 2460): FATAL EXCEPTION: main
09-02 04:36:12.526 E/AndroidRuntime( 2460): Process: com.tencent.qqpimsecure, PID: 2460
09-02 04:36:12.526 E/AndroidRuntime( 2460): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at android.os.Looper.loop(Looper.java:164)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 04:36:12.526 E/AndroidRuntime( 2460): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	... 8 more
09-02 04:36:12.526 E/AndroidRuntime( 2460): Caused by: java.lang.reflect.UndeclaredThrowableException
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at $Proxy5.init(Unknown Source)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	... 12 more
09-02 04:36:12.526 E/AndroidRuntime( 2460): Caused by: java.lang.reflect.InvocationTargetException
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	... 16 more
09-02 04:36:12.526 E/AndroidRuntime( 2460): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{3f840f3 u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at epetrp.b.c(SourceFile:8)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	at epetrp.c.init(SourceFile:1)
09-02 04:36:12.526 E/AndroidRuntime( 2460): 	... 19 more
09-02 04:36:17.501 E/AndroidRuntime( 2460): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-02 04:36:17.501 E/AndroidRuntime( 2460): Process: com.tencent.qqpimsecure, PID: 2460
09-02 04:36:17.501 E/AndroidRuntime( 2460): java.lang.InternalError: Thread starting during runtime shutdown
09-02 04:36:17.501 E/AndroidRuntime( 2460): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 04:36:17.501 E/AndroidRuntime( 2460): 	at java.lang.Thread.start(Thread.java:733)
09-02 04:36:17.501 E/AndroidRuntime( 2460): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 04:36:17.501 E/AndroidRuntime( 2460): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 04:36:17.501 E/AndroidRuntime( 2460): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 04:36:17.501 E/AndroidRuntime( 2460): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 04:36:17.501 E/AndroidRuntime( 2460): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 04:36:17.501 E/AndroidRuntime( 2460): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 04:36:17.501 E/AndroidRuntime( 2460): 	at tcs.bca.<init>(SourceFile:24)
09-02 04:36:17.501 E/AndroidRuntime( 2460): 	at tcs.bcb.dv(SourceFile:157)
09-02 04:36:17.501 E/AndroidRuntime( 2460): 	at tcs.bcb.b(SourceFile:135)
09-02 04:36:17.501 E/AndroidRuntime( 2460): 	at tcs.bcb.uF(SourceFile:229)
09-02 04:36:17.501 E/AndroidRuntime( 2460): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-02 04:36:17.501 E/AndroidRuntime( 2460): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 04:36:17.501 E/AndroidRuntime( 2460): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 04:36:17.501 E/AndroidRuntime( 2460): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-02 04:36:17.501 E/AndroidRuntime( 2460): 	at android.os.Looper.loop(Looper.java:164)
09-02 04:36:17.501 E/AndroidRuntime( 2460): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 04:36:17.501 E/AndroidRuntime( 2460): 	at tcs.alk.run(SourceFile:79)
09-02 04:36:17.530 E/AndroidRuntime( 2460): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-02 04:36:17.530 E/AndroidRuntime( 2460): Process: com.tencent.qqpimsecure, PID: 2460
09-02 04:36:17.530 E/AndroidRuntime( 2460): java.lang.reflect.UndeclaredThrowableException
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at $Proxy6.getPreferenceService(Unknown Source)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at epmt.j.c(SourceFile:1)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at epmt.c.a(SourceFile:2)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at epmt.g.l(SourceFile:99)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at epmt.g.a(SourceFile:2)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at epmt.g$c.handleMessage(SourceFile:1)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at android.os.Looper.loop(Looper.java:164)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at tcs.alk.run(SourceFile:79)
09-02 04:36:17.530 E/AndroidRuntime( 2460): Caused by: java.lang.reflect.InvocationTargetException
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	... 10 more
09-02 04:36:17.530 E/AndroidRuntime( 2460): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at java.lang.Thread.start(Thread.java:733)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at tcs.eiv.aq(SourceFile:111)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at tcs.ahr.<init>(SourceFile:16)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-02 04:36:17.530 E/AndroidRuntime( 2460): 	... 13 more
09-02 04:36:22.350 E/AndroidRuntime( 2670): FATAL EXCEPTION: main
09-02 04:36:22.350 E/AndroidRuntime( 2670): Process: com.tencent.qqpimsecure, PID: 2670
09-02 04:36:22.350 E/AndroidRuntime( 2670): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at android.os.Looper.loop(Looper.java:164)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 04:36:22.350 E/AndroidRuntime( 2670): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	... 8 more
09-02 04:36:22.350 E/AndroidRuntime( 2670): Caused by: java.lang.reflect.UndeclaredThrowableException
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at $Proxy5.init(Unknown Source)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	... 12 more
09-02 04:36:22.350 E/AndroidRuntime( 2670): Caused by: java.lang.reflect.InvocationTargetException
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	... 16 more
09-02 04:36:22.350 E/AndroidRuntime( 2670): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{d694604 u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at epetrp.b.c(SourceFile:8)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	at epetrp.c.init(SourceFile:1)
09-02 04:36:22.350 E/AndroidRuntime( 2670): 	... 19 more
09-02 04:36:27.343 E/AndroidRuntime( 2670): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-02 04:36:27.343 E/AndroidRuntime( 2670): Process: com.tencent.qqpimsecure, PID: 2670
09-02 04:36:27.343 E/AndroidRuntime( 2670): java.lang.InternalError: Thread starting during runtime shutdown
09-02 04:36:27.343 E/AndroidRuntime( 2670): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 04:36:27.343 E/AndroidRuntime( 2670): 	at java.lang.Thread.start(Thread.java:733)
09-02 04:36:27.343 E/AndroidRuntime( 2670): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 04:36:27.343 E/AndroidRuntime( 2670): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 04:36:27.343 E/AndroidRuntime( 2670): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 04:36:27.343 E/AndroidRuntime( 2670): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 04:36:27.343 E/AndroidRuntime( 2670): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 04:36:27.343 E/AndroidRuntime( 2670): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 04:36:27.343 E/AndroidRuntime( 2670): 	at tcs.bca.<init>(SourceFile:24)
09-02 04:36:27.343 E/AndroidRuntime( 2670): 	at tcs.bcb.dv(SourceFile:157)
09-02 04:36:27.343 E/AndroidRuntime( 2670): 	at tcs.bcb.b(SourceFile:135)
09-02 04:36:27.343 E/AndroidRuntime( 2670): 	at tcs.bcb.uF(SourceFile:229)
09-02 04:36:27.343 E/AndroidRuntime( 2670): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-02 04:36:27.343 E/AndroidRuntime( 2670): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 04:36:27.343 E/AndroidRuntime( 2670): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 04:36:27.343 E/AndroidRuntime( 2670): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-02 04:36:27.343 E/AndroidRuntime( 2670): 	at android.os.Looper.loop(Looper.java:164)
09-02 04:36:27.343 E/AndroidRuntime( 2670): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 04:36:27.343 E/AndroidRuntime( 2670): 	at tcs.alk.run(SourceFile:79)
09-02 04:36:27.356 E/AndroidRuntime( 2670): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-02 04:36:27.356 E/AndroidRuntime( 2670): Process: com.tencent.qqpimsecure, PID: 2670
09-02 04:36:27.356 E/AndroidRuntime( 2670): java.lang.reflect.UndeclaredThrowableException
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at $Proxy6.getPreferenceService(Unknown Source)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at epmt.j.c(SourceFile:1)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at epmt.c.a(SourceFile:2)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at epmt.g.l(SourceFile:99)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at epmt.g.a(SourceFile:2)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at epmt.g$c.handleMessage(SourceFile:1)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at android.os.Looper.loop(Looper.java:164)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at tcs.alk.run(SourceFile:79)
09-02 04:36:27.356 E/AndroidRuntime( 2670): Caused by: java.lang.reflect.InvocationTargetException
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	... 10 more
09-02 04:36:27.356 E/AndroidRuntime( 2670): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at java.lang.Thread.start(Thread.java:733)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at tcs.eiv.aq(SourceFile:111)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at tcs.ahr.<init>(SourceFile:16)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-02 04:36:27.356 E/AndroidRuntime( 2670): 	... 13 more
09-02 04:36:44.253 E/AndroidRuntime( 2940): FATAL EXCEPTION: main
09-02 04:36:44.253 E/AndroidRuntime( 2940): Process: com.tencent.qqpimsecure, PID: 2940
09-02 04:36:44.253 E/AndroidRuntime( 2940): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at android.os.Looper.loop(Looper.java:164)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 04:36:44.253 E/AndroidRuntime( 2940): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	... 8 more
09-02 04:36:44.253 E/AndroidRuntime( 2940): Caused by: java.lang.reflect.UndeclaredThrowableException
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at $Proxy5.init(Unknown Source)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	... 12 more
09-02 04:36:44.253 E/AndroidRuntime( 2940): Caused by: java.lang.reflect.InvocationTargetException
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	... 16 more
09-02 04:36:44.253 E/AndroidRuntime( 2940): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{424b7f0 u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at epetrp.b.c(SourceFile:8)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	at epetrp.c.init(SourceFile:1)
09-02 04:36:44.253 E/AndroidRuntime( 2940): 	... 19 more
09-02 04:36:49.249 E/AndroidRuntime( 2940): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-02 04:36:49.249 E/AndroidRuntime( 2940): Process: com.tencent.qqpimsecure, PID: 2940
09-02 04:36:49.249 E/AndroidRuntime( 2940): java.lang.InternalError: Thread starting during runtime shutdown
09-02 04:36:49.249 E/AndroidRuntime( 2940): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 04:36:49.249 E/AndroidRuntime( 2940): 	at java.lang.Thread.start(Thread.java:733)
09-02 04:36:49.249 E/AndroidRuntime( 2940): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 04:36:49.249 E/AndroidRuntime( 2940): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 04:36:49.249 E/AndroidRuntime( 2940): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 04:36:49.249 E/AndroidRuntime( 2940): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 04:36:49.249 E/AndroidRuntime( 2940): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 04:36:49.249 E/AndroidRuntime( 2940): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 04:36:49.249 E/AndroidRuntime( 2940): 	at tcs.bca.<init>(SourceFile:24)
09-02 04:36:49.249 E/AndroidRuntime( 2940): 	at tcs.bcb.dv(SourceFile:157)
09-02 04:36:49.249 E/AndroidRuntime( 2940): 	at tcs.bcb.b(SourceFile:135)
09-02 04:36:49.249 E/AndroidRuntime( 2940): 	at tcs.bcb.uF(SourceFile:229)
09-02 04:36:49.249 E/AndroidRuntime( 2940): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-02 04:36:49.249 E/AndroidRuntime( 2940): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 04:36:49.249 E/AndroidRuntime( 2940): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 04:36:49.249 E/AndroidRuntime( 2940): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-02 04:36:49.249 E/AndroidRuntime( 2940): 	at android.os.Looper.loop(Looper.java:164)
09-02 04:36:49.249 E/AndroidRuntime( 2940): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 04:36:49.249 E/AndroidRuntime( 2940): 	at tcs.alk.run(SourceFile:79)
09-02 04:36:49.263 E/AndroidRuntime( 2940): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-02 04:36:49.263 E/AndroidRuntime( 2940): Process: com.tencent.qqpimsecure, PID: 2940
09-02 04:36:49.263 E/AndroidRuntime( 2940): java.lang.reflect.UndeclaredThrowableException
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at $Proxy6.getPreferenceService(Unknown Source)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at epmt.j.c(SourceFile:1)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at epmt.c.a(SourceFile:2)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at epmt.g.l(SourceFile:99)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at epmt.g.a(SourceFile:2)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at epmt.g$c.handleMessage(SourceFile:1)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at android.os.Looper.loop(Looper.java:164)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at tcs.alk.run(SourceFile:79)
09-02 04:36:49.263 E/AndroidRuntime( 2940): Caused by: java.lang.reflect.InvocationTargetException
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	... 10 more
09-02 04:36:49.263 E/AndroidRuntime( 2940): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at java.lang.Thread.start(Thread.java:733)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at tcs.eiv.aq(SourceFile:111)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at tcs.ahr.<init>(SourceFile:16)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-02 04:36:49.263 E/AndroidRuntime( 2940): 	... 13 more
09-02 04:37:54.243 E/AndroidRuntime( 3357): FATAL EXCEPTION: main
09-02 04:37:54.243 E/AndroidRuntime( 3357): Process: com.tencent.qqpimsecure, PID: 3357
09-02 04:37:54.243 E/AndroidRuntime( 3357): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at android.os.Looper.loop(Looper.java:164)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 04:37:54.243 E/AndroidRuntime( 3357): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	... 8 more
09-02 04:37:54.243 E/AndroidRuntime( 3357): Caused by: java.lang.reflect.UndeclaredThrowableException
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at $Proxy5.init(Unknown Source)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	... 12 more
09-02 04:37:54.243 E/AndroidRuntime( 3357): Caused by: java.lang.reflect.InvocationTargetException
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	... 16 more
09-02 04:37:54.243 E/AndroidRuntime( 3357): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{2c575e1 u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at epetrp.b.c(SourceFile:8)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	at epetrp.c.init(SourceFile:1)
09-02 04:37:54.243 E/AndroidRuntime( 3357): 	... 19 more
09-02 04:37:59.240 E/AndroidRuntime( 3357): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-02 04:37:59.240 E/AndroidRuntime( 3357): Process: com.tencent.qqpimsecure, PID: 3357
09-02 04:37:59.240 E/AndroidRuntime( 3357): java.lang.InternalError: Thread starting during runtime shutdown
09-02 04:37:59.240 E/AndroidRuntime( 3357): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 04:37:59.240 E/AndroidRuntime( 3357): 	at java.lang.Thread.start(Thread.java:733)
09-02 04:37:59.240 E/AndroidRuntime( 3357): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 04:37:59.240 E/AndroidRuntime( 3357): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 04:37:59.240 E/AndroidRuntime( 3357): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 04:37:59.240 E/AndroidRuntime( 3357): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 04:37:59.240 E/AndroidRuntime( 3357): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 04:37:59.240 E/AndroidRuntime( 3357): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 04:37:59.240 E/AndroidRuntime( 3357): 	at tcs.bca.<init>(SourceFile:24)
09-02 04:37:59.240 E/AndroidRuntime( 3357): 	at tcs.bcb.dv(SourceFile:157)
09-02 04:37:59.240 E/AndroidRuntime( 3357): 	at tcs.bcb.b(SourceFile:135)
09-02 04:37:59.240 E/AndroidRuntime( 3357): 	at tcs.bcb.uF(SourceFile:229)
09-02 04:37:59.240 E/AndroidRuntime( 3357): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-02 04:37:59.240 E/AndroidRuntime( 3357): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 04:37:59.240 E/AndroidRuntime( 3357): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 04:37:59.240 E/AndroidRuntime( 3357): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-02 04:37:59.240 E/AndroidRuntime( 3357): 	at android.os.Looper.loop(Looper.java:164)
09-02 04:37:59.240 E/AndroidRuntime( 3357): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 04:37:59.240 E/AndroidRuntime( 3357): 	at tcs.alk.run(SourceFile:79)
09-02 04:37:59.252 E/AndroidRuntime( 3357): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-02 04:37:59.252 E/AndroidRuntime( 3357): Process: com.tencent.qqpimsecure, PID: 3357
09-02 04:37:59.252 E/AndroidRuntime( 3357): java.lang.reflect.UndeclaredThrowableException
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at $Proxy6.getPreferenceService(Unknown Source)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at epmt.j.c(SourceFile:1)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at epmt.c.a(SourceFile:2)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at epmt.g.l(SourceFile:99)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at epmt.g.a(SourceFile:2)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at epmt.g$c.handleMessage(SourceFile:1)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at android.os.Looper.loop(Looper.java:164)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at tcs.alk.run(SourceFile:79)
09-02 04:37:59.252 E/AndroidRuntime( 3357): Caused by: java.lang.reflect.InvocationTargetException
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	... 10 more
09-02 04:37:59.252 E/AndroidRuntime( 3357): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at java.lang.Thread.start(Thread.java:733)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at tcs.eiv.aq(SourceFile:111)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at tcs.ahr.<init>(SourceFile:16)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-02 04:37:59.252 E/AndroidRuntime( 3357): 	... 13 more
09-02 09:36:05.747 E/AndroidRuntime( 2791): FATAL EXCEPTION: main
09-02 09:36:05.747 E/AndroidRuntime( 2791): Process: com.tencent.qqpimsecure, PID: 2791
09-02 09:36:05.747 E/AndroidRuntime( 2791): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at android.os.Looper.loop(Looper.java:164)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 09:36:05.747 E/AndroidRuntime( 2791): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	... 8 more
09-02 09:36:05.747 E/AndroidRuntime( 2791): Caused by: java.lang.reflect.UndeclaredThrowableException
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at $Proxy6.init(Unknown Source)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	... 12 more
09-02 09:36:05.747 E/AndroidRuntime( 2791): Caused by: java.lang.reflect.InvocationTargetException
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	... 16 more
09-02 09:36:05.747 E/AndroidRuntime( 2791): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{98953f1 u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at epetrp.b.c(SourceFile:8)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	at epetrp.c.init(SourceFile:1)
09-02 09:36:05.747 E/AndroidRuntime( 2791): 	... 19 more
09-02 09:36:10.728 E/AndroidRuntime( 2791): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-02 09:36:10.728 E/AndroidRuntime( 2791): Process: com.tencent.qqpimsecure, PID: 2791
09-02 09:36:10.728 E/AndroidRuntime( 2791): java.lang.InternalError: Thread starting during runtime shutdown
09-02 09:36:10.728 E/AndroidRuntime( 2791): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 09:36:10.728 E/AndroidRuntime( 2791): 	at java.lang.Thread.start(Thread.java:733)
09-02 09:36:10.728 E/AndroidRuntime( 2791): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 09:36:10.728 E/AndroidRuntime( 2791): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 09:36:10.728 E/AndroidRuntime( 2791): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 09:36:10.728 E/AndroidRuntime( 2791): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 09:36:10.728 E/AndroidRuntime( 2791): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 09:36:10.728 E/AndroidRuntime( 2791): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 09:36:10.728 E/AndroidRuntime( 2791): 	at tcs.bca.<init>(SourceFile:24)
09-02 09:36:10.728 E/AndroidRuntime( 2791): 	at tcs.bcb.dv(SourceFile:157)
09-02 09:36:10.728 E/AndroidRuntime( 2791): 	at tcs.bcb.b(SourceFile:135)
09-02 09:36:10.728 E/AndroidRuntime( 2791): 	at tcs.bcb.uF(SourceFile:229)
09-02 09:36:10.728 E/AndroidRuntime( 2791): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-02 09:36:10.728 E/AndroidRuntime( 2791): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 09:36:10.728 E/AndroidRuntime( 2791): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 09:36:10.728 E/AndroidRuntime( 2791): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-02 09:36:10.728 E/AndroidRuntime( 2791): 	at android.os.Looper.loop(Looper.java:164)
09-02 09:36:10.728 E/AndroidRuntime( 2791): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 09:36:10.728 E/AndroidRuntime( 2791): 	at tcs.alk.run(SourceFile:79)
09-02 09:36:10.750 E/AndroidRuntime( 2791): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-02 09:36:10.750 E/AndroidRuntime( 2791): Process: com.tencent.qqpimsecure, PID: 2791
09-02 09:36:10.750 E/AndroidRuntime( 2791): java.lang.reflect.UndeclaredThrowableException
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at $Proxy5.getPreferenceService(Unknown Source)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at epmt.j.c(SourceFile:1)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at epmt.c.a(SourceFile:2)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at epmt.g.l(SourceFile:99)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at epmt.g.a(SourceFile:2)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at epmt.g$c.handleMessage(SourceFile:1)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at android.os.Looper.loop(Looper.java:164)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at tcs.alk.run(SourceFile:79)
09-02 09:36:10.750 E/AndroidRuntime( 2791): Caused by: java.lang.reflect.InvocationTargetException
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	... 10 more
09-02 09:36:10.750 E/AndroidRuntime( 2791): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at java.lang.Thread.start(Thread.java:733)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at tcs.eiv.aq(SourceFile:111)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at tcs.ahr.<init>(SourceFile:16)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-02 09:36:10.750 E/AndroidRuntime( 2791): 	... 13 more
09-02 09:36:12.679 E/AndroidRuntime( 3024): FATAL EXCEPTION: main
09-02 09:36:12.679 E/AndroidRuntime( 3024): Process: com.tencent.qqpimsecure, PID: 3024
09-02 09:36:12.679 E/AndroidRuntime( 3024): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at android.os.Looper.loop(Looper.java:164)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 09:36:12.679 E/AndroidRuntime( 3024): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	... 8 more
09-02 09:36:12.679 E/AndroidRuntime( 3024): Caused by: java.lang.reflect.UndeclaredThrowableException
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at $Proxy6.init(Unknown Source)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	... 12 more
09-02 09:36:12.679 E/AndroidRuntime( 3024): Caused by: java.lang.reflect.InvocationTargetException
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	... 16 more
09-02 09:36:12.679 E/AndroidRuntime( 3024): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{d440156 u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at epetrp.b.c(SourceFile:8)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	at epetrp.c.init(SourceFile:1)
09-02 09:36:12.679 E/AndroidRuntime( 3024): 	... 19 more
09-02 09:36:17.667 E/AndroidRuntime( 3024): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-02 09:36:17.667 E/AndroidRuntime( 3024): Process: com.tencent.qqpimsecure, PID: 3024
09-02 09:36:17.667 E/AndroidRuntime( 3024): java.lang.InternalError: Thread starting during runtime shutdown
09-02 09:36:17.667 E/AndroidRuntime( 3024): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 09:36:17.667 E/AndroidRuntime( 3024): 	at java.lang.Thread.start(Thread.java:733)
09-02 09:36:17.667 E/AndroidRuntime( 3024): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 09:36:17.667 E/AndroidRuntime( 3024): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 09:36:17.667 E/AndroidRuntime( 3024): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 09:36:17.667 E/AndroidRuntime( 3024): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 09:36:17.667 E/AndroidRuntime( 3024): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 09:36:17.667 E/AndroidRuntime( 3024): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 09:36:17.667 E/AndroidRuntime( 3024): 	at tcs.bca.<init>(SourceFile:24)
09-02 09:36:17.667 E/AndroidRuntime( 3024): 	at tcs.bcb.dv(SourceFile:157)
09-02 09:36:17.667 E/AndroidRuntime( 3024): 	at tcs.bcb.b(SourceFile:135)
09-02 09:36:17.667 E/AndroidRuntime( 3024): 	at tcs.bcb.uF(SourceFile:229)
09-02 09:36:17.667 E/AndroidRuntime( 3024): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-02 09:36:17.667 E/AndroidRuntime( 3024): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 09:36:17.667 E/AndroidRuntime( 3024): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 09:36:17.667 E/AndroidRuntime( 3024): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-02 09:36:17.667 E/AndroidRuntime( 3024): 	at android.os.Looper.loop(Looper.java:164)
09-02 09:36:17.667 E/AndroidRuntime( 3024): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 09:36:17.667 E/AndroidRuntime( 3024): 	at tcs.alk.run(SourceFile:79)
09-02 09:36:17.686 E/AndroidRuntime( 3024): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-02 09:36:17.686 E/AndroidRuntime( 3024): Process: com.tencent.qqpimsecure, PID: 3024
09-02 09:36:17.686 E/AndroidRuntime( 3024): java.lang.reflect.UndeclaredThrowableException
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at $Proxy5.getPreferenceService(Unknown Source)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at epmt.j.c(SourceFile:1)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at epmt.c.a(SourceFile:2)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at epmt.g.l(SourceFile:99)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at epmt.g.a(SourceFile:2)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at epmt.g$c.handleMessage(SourceFile:1)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at android.os.Looper.loop(Looper.java:164)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at tcs.alk.run(SourceFile:79)
09-02 09:36:17.686 E/AndroidRuntime( 3024): Caused by: java.lang.reflect.InvocationTargetException
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	... 10 more
09-02 09:36:17.686 E/AndroidRuntime( 3024): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at java.lang.Thread.start(Thread.java:733)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at tcs.eiv.aq(SourceFile:111)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at tcs.ahr.<init>(SourceFile:16)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-02 09:36:17.686 E/AndroidRuntime( 3024): 	... 13 more
09-02 09:36:22.519 E/AndroidRuntime( 3278): FATAL EXCEPTION: main
09-02 09:36:22.519 E/AndroidRuntime( 3278): Process: com.tencent.qqpimsecure, PID: 3278
09-02 09:36:22.519 E/AndroidRuntime( 3278): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at android.os.Looper.loop(Looper.java:164)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 09:36:22.519 E/AndroidRuntime( 3278): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	... 8 more
09-02 09:36:22.519 E/AndroidRuntime( 3278): Caused by: java.lang.reflect.UndeclaredThrowableException
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at $Proxy6.init(Unknown Source)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	... 12 more
09-02 09:36:22.519 E/AndroidRuntime( 3278): Caused by: java.lang.reflect.InvocationTargetException
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	... 16 more
09-02 09:36:22.519 E/AndroidRuntime( 3278): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{251a4bb u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at epetrp.b.c(SourceFile:8)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	at epetrp.c.init(SourceFile:1)
09-02 09:36:22.519 E/AndroidRuntime( 3278): 	... 19 more
09-02 09:36:27.498 E/AndroidRuntime( 3278): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-02 09:36:27.498 E/AndroidRuntime( 3278): Process: com.tencent.qqpimsecure, PID: 3278
09-02 09:36:27.498 E/AndroidRuntime( 3278): java.lang.InternalError: Thread starting during runtime shutdown
09-02 09:36:27.498 E/AndroidRuntime( 3278): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 09:36:27.498 E/AndroidRuntime( 3278): 	at java.lang.Thread.start(Thread.java:733)
09-02 09:36:27.498 E/AndroidRuntime( 3278): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 09:36:27.498 E/AndroidRuntime( 3278): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 09:36:27.498 E/AndroidRuntime( 3278): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 09:36:27.498 E/AndroidRuntime( 3278): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 09:36:27.498 E/AndroidRuntime( 3278): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 09:36:27.498 E/AndroidRuntime( 3278): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 09:36:27.498 E/AndroidRuntime( 3278): 	at tcs.bca.<init>(SourceFile:24)
09-02 09:36:27.498 E/AndroidRuntime( 3278): 	at tcs.bcb.dv(SourceFile:157)
09-02 09:36:27.498 E/AndroidRuntime( 3278): 	at tcs.bcb.b(SourceFile:135)
09-02 09:36:27.498 E/AndroidRuntime( 3278): 	at tcs.bcb.uF(SourceFile:229)
09-02 09:36:27.498 E/AndroidRuntime( 3278): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-02 09:36:27.498 E/AndroidRuntime( 3278): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 09:36:27.498 E/AndroidRuntime( 3278): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 09:36:27.498 E/AndroidRuntime( 3278): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-02 09:36:27.498 E/AndroidRuntime( 3278): 	at android.os.Looper.loop(Looper.java:164)
09-02 09:36:27.498 E/AndroidRuntime( 3278): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 09:36:27.498 E/AndroidRuntime( 3278): 	at tcs.alk.run(SourceFile:79)
09-02 09:36:27.524 E/AndroidRuntime( 3278): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-02 09:36:27.524 E/AndroidRuntime( 3278): Process: com.tencent.qqpimsecure, PID: 3278
09-02 09:36:27.524 E/AndroidRuntime( 3278): java.lang.reflect.UndeclaredThrowableException
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at $Proxy5.getPreferenceService(Unknown Source)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at epmt.j.c(SourceFile:1)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at epmt.c.a(SourceFile:2)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at epmt.g.l(SourceFile:99)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at epmt.g.a(SourceFile:2)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at epmt.g$c.handleMessage(SourceFile:1)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at android.os.Looper.loop(Looper.java:164)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at tcs.alk.run(SourceFile:79)
09-02 09:36:27.524 E/AndroidRuntime( 3278): Caused by: java.lang.reflect.InvocationTargetException
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	... 10 more
09-02 09:36:27.524 E/AndroidRuntime( 3278): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at java.lang.Thread.start(Thread.java:733)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at tcs.eiv.aq(SourceFile:111)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at tcs.ahr.<init>(SourceFile:16)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-02 09:36:27.524 E/AndroidRuntime( 3278): 	... 13 more
09-02 09:36:44.374 E/AndroidRuntime( 3604): FATAL EXCEPTION: main
09-02 09:36:44.374 E/AndroidRuntime( 3604): Process: com.tencent.qqpimsecure, PID: 3604
09-02 09:36:44.374 E/AndroidRuntime( 3604): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at android.os.Looper.loop(Looper.java:164)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 09:36:44.374 E/AndroidRuntime( 3604): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	... 8 more
09-02 09:36:44.374 E/AndroidRuntime( 3604): Caused by: java.lang.reflect.UndeclaredThrowableException
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at $Proxy5.init(Unknown Source)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	... 12 more
09-02 09:36:44.374 E/AndroidRuntime( 3604): Caused by: java.lang.reflect.InvocationTargetException
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	... 16 more
09-02 09:36:44.374 E/AndroidRuntime( 3604): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{592d104 u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at epetrp.b.c(SourceFile:8)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	at epetrp.c.init(SourceFile:1)
09-02 09:36:44.374 E/AndroidRuntime( 3604): 	... 19 more
09-02 09:36:49.356 E/AndroidRuntime( 3604): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-02 09:36:49.356 E/AndroidRuntime( 3604): Process: com.tencent.qqpimsecure, PID: 3604
09-02 09:36:49.356 E/AndroidRuntime( 3604): java.lang.InternalError: Thread starting during runtime shutdown
09-02 09:36:49.356 E/AndroidRuntime( 3604): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 09:36:49.356 E/AndroidRuntime( 3604): 	at java.lang.Thread.start(Thread.java:733)
09-02 09:36:49.356 E/AndroidRuntime( 3604): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 09:36:49.356 E/AndroidRuntime( 3604): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 09:36:49.356 E/AndroidRuntime( 3604): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 09:36:49.356 E/AndroidRuntime( 3604): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 09:36:49.356 E/AndroidRuntime( 3604): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 09:36:49.356 E/AndroidRuntime( 3604): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 09:36:49.356 E/AndroidRuntime( 3604): 	at tcs.bca.<init>(SourceFile:24)
09-02 09:36:49.356 E/AndroidRuntime( 3604): 	at tcs.bcb.dv(SourceFile:157)
09-02 09:36:49.356 E/AndroidRuntime( 3604): 	at tcs.bcb.b(SourceFile:135)
09-02 09:36:49.356 E/AndroidRuntime( 3604): 	at tcs.bcb.uF(SourceFile:229)
09-02 09:36:49.356 E/AndroidRuntime( 3604): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-02 09:36:49.356 E/AndroidRuntime( 3604): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 09:36:49.356 E/AndroidRuntime( 3604): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 09:36:49.356 E/AndroidRuntime( 3604): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-02 09:36:49.356 E/AndroidRuntime( 3604): 	at android.os.Looper.loop(Looper.java:164)
09-02 09:36:49.356 E/AndroidRuntime( 3604): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 09:36:49.356 E/AndroidRuntime( 3604): 	at tcs.alk.run(SourceFile:79)
09-02 09:36:49.378 E/AndroidRuntime( 3604): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-02 09:36:49.378 E/AndroidRuntime( 3604): Process: com.tencent.qqpimsecure, PID: 3604
09-02 09:36:49.378 E/AndroidRuntime( 3604): java.lang.reflect.UndeclaredThrowableException
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at $Proxy6.getPreferenceService(Unknown Source)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at epmt.j.c(SourceFile:1)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at epmt.c.a(SourceFile:2)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at epmt.g.l(SourceFile:99)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at epmt.g.a(SourceFile:2)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at epmt.g$c.handleMessage(SourceFile:1)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at android.os.Looper.loop(Looper.java:164)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at tcs.alk.run(SourceFile:79)
09-02 09:36:49.378 E/AndroidRuntime( 3604): Caused by: java.lang.reflect.InvocationTargetException
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	... 10 more
09-02 09:36:49.378 E/AndroidRuntime( 3604): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at java.lang.Thread.start(Thread.java:733)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at tcs.eiv.aq(SourceFile:111)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at tcs.ahr.<init>(SourceFile:16)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-02 09:36:49.378 E/AndroidRuntime( 3604): 	... 13 more
09-02 09:37:54.258 E/AndroidRuntime( 3943): FATAL EXCEPTION: main
09-02 09:37:54.258 E/AndroidRuntime( 3943): Process: com.tencent.qqpimsecure, PID: 3943
09-02 09:37:54.258 E/AndroidRuntime( 3943): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at android.os.Looper.loop(Looper.java:164)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 09:37:54.258 E/AndroidRuntime( 3943): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	... 8 more
09-02 09:37:54.258 E/AndroidRuntime( 3943): Caused by: java.lang.reflect.UndeclaredThrowableException
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at $Proxy6.init(Unknown Source)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	... 12 more
09-02 09:37:54.258 E/AndroidRuntime( 3943): Caused by: java.lang.reflect.InvocationTargetException
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	... 16 more
09-02 09:37:54.258 E/AndroidRuntime( 3943): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{273d3e5 u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at epetrp.b.c(SourceFile:8)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	at epetrp.c.init(SourceFile:1)
09-02 09:37:54.258 E/AndroidRuntime( 3943): 	... 19 more
09-02 09:37:59.242 E/AndroidRuntime( 3943): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-02 09:37:59.242 E/AndroidRuntime( 3943): Process: com.tencent.qqpimsecure, PID: 3943
09-02 09:37:59.242 E/AndroidRuntime( 3943): java.lang.InternalError: Thread starting during runtime shutdown
09-02 09:37:59.242 E/AndroidRuntime( 3943): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 09:37:59.242 E/AndroidRuntime( 3943): 	at java.lang.Thread.start(Thread.java:733)
09-02 09:37:59.242 E/AndroidRuntime( 3943): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 09:37:59.242 E/AndroidRuntime( 3943): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 09:37:59.242 E/AndroidRuntime( 3943): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 09:37:59.242 E/AndroidRuntime( 3943): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 09:37:59.242 E/AndroidRuntime( 3943): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 09:37:59.242 E/AndroidRuntime( 3943): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 09:37:59.242 E/AndroidRuntime( 3943): 	at tcs.bca.<init>(SourceFile:24)
09-02 09:37:59.242 E/AndroidRuntime( 3943): 	at tcs.bcb.dv(SourceFile:157)
09-02 09:37:59.242 E/AndroidRuntime( 3943): 	at tcs.bcb.b(SourceFile:135)
09-02 09:37:59.242 E/AndroidRuntime( 3943): 	at tcs.bcb.uF(SourceFile:229)
09-02 09:37:59.242 E/AndroidRuntime( 3943): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-02 09:37:59.242 E/AndroidRuntime( 3943): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 09:37:59.242 E/AndroidRuntime( 3943): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 09:37:59.242 E/AndroidRuntime( 3943): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-02 09:37:59.242 E/AndroidRuntime( 3943): 	at android.os.Looper.loop(Looper.java:164)
09-02 09:37:59.242 E/AndroidRuntime( 3943): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 09:37:59.242 E/AndroidRuntime( 3943): 	at tcs.alk.run(SourceFile:79)
09-02 09:37:59.262 E/AndroidRuntime( 3943): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-02 09:37:59.262 E/AndroidRuntime( 3943): Process: com.tencent.qqpimsecure, PID: 3943
09-02 09:37:59.262 E/AndroidRuntime( 3943): java.lang.reflect.UndeclaredThrowableException
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at $Proxy5.getPreferenceService(Unknown Source)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at epmt.j.c(SourceFile:1)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at epmt.c.a(SourceFile:2)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at epmt.g.l(SourceFile:99)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at epmt.g.a(SourceFile:2)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at epmt.g$c.handleMessage(SourceFile:1)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at android.os.Looper.loop(Looper.java:164)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at tcs.alk.run(SourceFile:79)
09-02 09:37:59.262 E/AndroidRuntime( 3943): Caused by: java.lang.reflect.InvocationTargetException
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	... 10 more
09-02 09:37:59.262 E/AndroidRuntime( 3943): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at java.lang.Thread.start(Thread.java:733)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at tcs.eiv.aq(SourceFile:111)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at tcs.ahr.<init>(SourceFile:16)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-02 09:37:59.262 E/AndroidRuntime( 3943): 	... 13 more
09-02 10:18:16.245 E/ActivityThread( 3253): Failed to find provider info for com.android.badge
09-02 10:18:16.264 E/ActivityThread( 3253): Failed to find provider info for com.android.badge
09-02 10:41:43.027 W/FileUtils(12578): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 10:41:43.051 W/FileUtils(12578): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 10:41:43.086 W/FileUtils(12578): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 10:41:43.091 W/FileUtils(12578): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 10:41:44.157 W/FileUtils(12578): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 10:41:44.186 W/FileUtils(12578): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 10:41:44.222 W/PackageParser(12578): Failed to parse /storage/emulated/0/tencent/tbs/backup/com.tencent.mm/x5.tbs.org
09-02 10:41:44.222 W/PackageParser(12578): java.io.FileNotFoundException: AndroidManifest.xml
09-02 10:41:44.222 W/PackageParser(12578): 	at android.content.res.AssetManager.openXmlAssetNative(Native Method)
09-02 10:41:44.222 W/PackageParser(12578): 	at android.content.res.AssetManager.openXmlBlockAsset(AssetManager.java:560)
09-02 10:41:44.222 W/PackageParser(12578): 	at android.content.res.AssetManager.openXmlResourceParser(AssetManager.java:528)
09-02 10:41:44.222 W/PackageParser(12578): 	at android.content.pm.PackageParser.parseApkLite(PackageParser.java:1773)
09-02 10:41:44.222 W/PackageParser(12578): 	at android.content.pm.PackageParser.parseMonolithicPackageLite(PackageParser.java:906)
09-02 10:41:44.222 W/PackageParser(12578): 	at android.content.pm.PackageParser.parseMonolithicPackage(PackageParser.java:1294)
09-02 10:41:44.222 W/PackageParser(12578): 	at android.content.pm.PackageManager.getPackageArchiveInfo(PackageManager.java:4693)
09-02 10:41:44.222 W/PackageParser(12578): 	at com.tencent.smtt.utils.a.a(Unknown Source:147)
09-02 10:41:44.222 W/PackageParser(12578): 	at com.tencent.smtt.utils.a.a(Unknown Source:21)
09-02 10:41:44.222 W/PackageParser(12578): 	at com.tencent.smtt.sdk.TbsDownloader.a(Unknown Source:65)
09-02 10:41:44.222 W/PackageParser(12578): 	at com.tencent.smtt.sdk.l.a(Unknown Source:71)
09-02 10:41:44.222 W/PackageParser(12578): 	at com.tencent.smtt.sdk.TbsDownloader.a(Unknown Source:1809)
09-02 10:41:44.222 W/PackageParser(12578): 	at com.tencent.smtt.sdk.TbsDownloader.b(Unknown Source:931)
09-02 10:41:44.222 W/PackageParser(12578): 	at com.tencent.smtt.sdk.TbsDownloader.a(Unknown Source:0)
09-02 10:41:44.222 W/PackageParser(12578): 	at com.tencent.smtt.sdk.TbsDownloader$2.handleMessage(Unknown Source:167)
09-02 10:41:44.222 W/PackageParser(12578): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 10:41:44.222 W/PackageParser(12578): 	at android.os.Looper.loop(Looper.java:164)
09-02 10:41:44.222 W/PackageParser(12578): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 10:41:44.564 W/FileUtils(12578): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 10:41:44.581 W/FileUtils(12578): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 10:41:44.599 W/FileUtils(12578): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 10:41:44.602 W/FileUtils(12578): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 10:41:47.508 E/ActivityThread(12838): Failed to find provider info for com.vivo.push.sdk.service.SystemPushConfig
09-02 11:34:53.552 W/FileUtils(20165): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:34:53.561 W/FileUtils(20165): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:34:53.568 W/FileUtils(20165): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:34:53.573 W/FileUtils(20165): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:34:54.019 W/FileUtils(20165): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:34:54.028 W/FileUtils(20165): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:34:54.058 W/PackageParser(20165): Failed to parse /storage/emulated/0/tencent/tbs/backup/com.tencent.mm/x5.tbs.org
09-02 11:34:54.058 W/PackageParser(20165): java.io.FileNotFoundException: AndroidManifest.xml
09-02 11:34:54.058 W/PackageParser(20165): 	at android.content.res.AssetManager.openXmlAssetNative(Native Method)
09-02 11:34:54.058 W/PackageParser(20165): 	at android.content.res.AssetManager.openXmlBlockAsset(AssetManager.java:560)
09-02 11:34:54.058 W/PackageParser(20165): 	at android.content.res.AssetManager.openXmlResourceParser(AssetManager.java:528)
09-02 11:34:54.058 W/PackageParser(20165): 	at android.content.pm.PackageParser.parseApkLite(PackageParser.java:1773)
09-02 11:34:54.058 W/PackageParser(20165): 	at android.content.pm.PackageParser.parseMonolithicPackageLite(PackageParser.java:906)
09-02 11:34:54.058 W/PackageParser(20165): 	at android.content.pm.PackageParser.parseMonolithicPackage(PackageParser.java:1294)
09-02 11:34:54.058 W/PackageParser(20165): 	at android.content.pm.PackageManager.getPackageArchiveInfo(PackageManager.java:4693)
09-02 11:34:54.058 W/PackageParser(20165): 	at com.tencent.smtt.utils.a.a(Unknown Source:147)
09-02 11:34:54.058 W/PackageParser(20165): 	at com.tencent.smtt.utils.a.a(Unknown Source:21)
09-02 11:34:54.058 W/PackageParser(20165): 	at com.tencent.smtt.sdk.TbsDownloader.a(Unknown Source:65)
09-02 11:34:54.058 W/PackageParser(20165): 	at com.tencent.smtt.sdk.l.a(Unknown Source:71)
09-02 11:34:54.058 W/PackageParser(20165): 	at com.tencent.smtt.sdk.TbsDownloader.a(Unknown Source:1767)
09-02 11:34:54.058 W/PackageParser(20165): 	at com.tencent.smtt.sdk.TbsDownloader.b(Unknown Source:917)
09-02 11:34:54.058 W/PackageParser(20165): 	at com.tencent.smtt.sdk.TbsDownloader.a(Unknown Source:0)
09-02 11:34:54.058 W/PackageParser(20165): 	at com.tencent.smtt.sdk.TbsDownloader$2.handleMessage(Unknown Source:165)
09-02 11:34:54.058 W/PackageParser(20165): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 11:34:54.058 W/PackageParser(20165): 	at android.os.Looper.loop(Looper.java:164)
09-02 11:34:54.058 W/PackageParser(20165): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 11:34:54.233 W/FileUtils(20165): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:34:54.235 W/FileUtils(20165): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:34:54.246 W/FileUtils(20165): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:34:54.247 W/FileUtils(20165): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:34:56.852 E/ActivityThread(20438): Failed to find provider info for com.vivo.push.sdk.service.SystemPushConfig
09-02 11:36:01.969 W/FileUtils(20969): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:36:01.990 W/FileUtils(20969): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:36:02.019 W/FileUtils(20969): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:36:02.023 W/FileUtils(20969): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:36:03.083 W/FileUtils(20969): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:36:03.119 W/FileUtils(20969): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:36:03.169 W/PackageParser(20969): Failed to parse /storage/emulated/0/tencent/tbs/backup/com.tencent.mm/x5.tbs.org
09-02 11:36:03.169 W/PackageParser(20969): java.io.FileNotFoundException: AndroidManifest.xml
09-02 11:36:03.169 W/PackageParser(20969): 	at android.content.res.AssetManager.openXmlAssetNative(Native Method)
09-02 11:36:03.169 W/PackageParser(20969): 	at android.content.res.AssetManager.openXmlBlockAsset(AssetManager.java:560)
09-02 11:36:03.169 W/PackageParser(20969): 	at android.content.res.AssetManager.openXmlResourceParser(AssetManager.java:528)
09-02 11:36:03.169 W/PackageParser(20969): 	at android.content.pm.PackageParser.parseApkLite(PackageParser.java:1773)
09-02 11:36:03.169 W/PackageParser(20969): 	at android.content.pm.PackageParser.parseMonolithicPackageLite(PackageParser.java:906)
09-02 11:36:03.169 W/PackageParser(20969): 	at android.content.pm.PackageParser.parseMonolithicPackage(PackageParser.java:1294)
09-02 11:36:03.169 W/PackageParser(20969): 	at android.content.pm.PackageManager.getPackageArchiveInfo(PackageManager.java:4693)
09-02 11:36:03.169 W/PackageParser(20969): 	at com.tencent.smtt.utils.a.a(Unknown Source:147)
09-02 11:36:03.169 W/PackageParser(20969): 	at com.tencent.smtt.utils.a.a(Unknown Source:21)
09-02 11:36:03.169 W/PackageParser(20969): 	at com.tencent.smtt.sdk.TbsDownloader.a(Unknown Source:65)
09-02 11:36:03.169 W/PackageParser(20969): 	at com.tencent.smtt.sdk.l.a(Unknown Source:71)
09-02 11:36:03.169 W/PackageParser(20969): 	at com.tencent.smtt.sdk.TbsDownloader.a(Unknown Source:1809)
09-02 11:36:03.169 W/PackageParser(20969): 	at com.tencent.smtt.sdk.TbsDownloader.b(Unknown Source:931)
09-02 11:36:03.169 W/PackageParser(20969): 	at com.tencent.smtt.sdk.TbsDownloader.a(Unknown Source:0)
09-02 11:36:03.169 W/PackageParser(20969): 	at com.tencent.smtt.sdk.TbsDownloader$2.handleMessage(Unknown Source:167)
09-02 11:36:03.169 W/PackageParser(20969): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 11:36:03.169 W/PackageParser(20969): 	at android.os.Looper.loop(Looper.java:164)
09-02 11:36:03.169 W/PackageParser(20969): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 11:36:03.565 W/FileUtils(20969): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:36:03.583 W/FileUtils(20969): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:36:03.599 W/FileUtils(20969): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:36:03.603 W/FileUtils(20969): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:36:05.998 E/ActivityThread(21214): Failed to find provider info for com.vivo.push.sdk.service.SystemPushConfig
09-02 11:46:32.703 W/FileUtils(24234): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:46:32.716 W/FileUtils(24234): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:46:32.722 W/FileUtils(24234): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:46:32.723 W/FileUtils(24234): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:46:33.197 W/FileUtils(24234): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:46:33.218 W/FileUtils(24234): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:46:33.283 W/PackageParser(24234): Failed to parse /storage/emulated/0/tencent/tbs/backup/com.tencent.mm/x5.tbs.org
09-02 11:46:33.283 W/PackageParser(24234): java.io.FileNotFoundException: AndroidManifest.xml
09-02 11:46:33.283 W/PackageParser(24234): 	at android.content.res.AssetManager.openXmlAssetNative(Native Method)
09-02 11:46:33.283 W/PackageParser(24234): 	at android.content.res.AssetManager.openXmlBlockAsset(AssetManager.java:560)
09-02 11:46:33.283 W/PackageParser(24234): 	at android.content.res.AssetManager.openXmlResourceParser(AssetManager.java:528)
09-02 11:46:33.283 W/PackageParser(24234): 	at android.content.pm.PackageParser.parseApkLite(PackageParser.java:1773)
09-02 11:46:33.283 W/PackageParser(24234): 	at android.content.pm.PackageParser.parseMonolithicPackageLite(PackageParser.java:906)
09-02 11:46:33.283 W/PackageParser(24234): 	at android.content.pm.PackageParser.parseMonolithicPackage(PackageParser.java:1294)
09-02 11:46:33.283 W/PackageParser(24234): 	at android.content.pm.PackageManager.getPackageArchiveInfo(PackageManager.java:4693)
09-02 11:46:33.283 W/PackageParser(24234): 	at com.tencent.smtt.utils.a.a(Unknown Source:146)
09-02 11:46:33.283 W/PackageParser(24234): 	at com.tencent.smtt.utils.a.a(Unknown Source:21)
09-02 11:46:33.283 W/PackageParser(24234): 	at com.tencent.smtt.sdk.TbsDownloader.a(Unknown Source:65)
09-02 11:46:33.283 W/PackageParser(24234): 	at com.tencent.smtt.sdk.l.a(Unknown Source:69)
09-02 11:46:33.283 W/PackageParser(24234): 	at com.tencent.smtt.sdk.TbsDownloader.a(Unknown Source:1731)
09-02 11:46:33.283 W/PackageParser(24234): 	at com.tencent.smtt.sdk.TbsDownloader.b(Unknown Source:913)
09-02 11:46:33.283 W/PackageParser(24234): 	at com.tencent.smtt.sdk.TbsDownloader.a(Unknown Source:0)
09-02 11:46:33.283 W/PackageParser(24234): 	at com.tencent.smtt.sdk.TbsDownloader$2.handleMessage(Unknown Source:164)
09-02 11:46:33.283 W/PackageParser(24234): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 11:46:33.283 W/PackageParser(24234): 	at android.os.Looper.loop(Looper.java:164)
09-02 11:46:33.283 W/PackageParser(24234): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 11:46:33.476 W/FileUtils(24234): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:46:33.480 W/FileUtils(24234): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:46:33.493 W/FileUtils(24234): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:46:33.494 W/FileUtils(24234): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 11:46:35.929 E/ActivityThread(24507): Failed to find provider info for com.vivo.push.sdk.service.SystemPushConfig
09-02 12:38:07.384 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher2.permission.READ_SETTINGS in package: com.tencent.mobileqq at: Binary XML file line #83
09-02 12:38:07.385 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WRITE_CONTACTS in package: com.tencent.mobileqq at: Binary XML file line #114
09-02 12:38:07.391 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #185
09-02 12:38:07.391 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CHANGE_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #192
09-02 12:38:07.391 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.INTERNET in package: com.tencent.mobileqq at: Binary XML file line #193
09-02 12:38:07.391 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #194
09-02 12:38:07.391 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_NETWORK_STATE in package: com.tencent.mobileqq at: Binary XML file line #195
09-02 12:38:07.391 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CAMERA in package: com.tencent.mobileqq at: Binary XML file line #199
09-02 12:38:07.391 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.tencent.mobileqq at: Binary XML file line #200
09-02 12:38:07.392 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WAKE_LOCK in package: com.tencent.mobileqq at: Binary XML file line #201
09-02 12:38:07.392 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher.permission.INSTALL_SHORTCUT in package: com.tencent.mobileqq at: Binary XML file line #202
09-02 12:38:07.392 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.RECEIVE_BOOT_COMPLETED in package: com.tencent.mobileqq at: Binary XML file line #203
09-02 12:38:07.392 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #205
09-02 12:38:07.404 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Android/data/com.tencent.mobileqq/Tencent/TMAssistantSDK/Download/com.tencent.mobileqq/AndroidBBPJQQ_8.8.17.5770_537084958_bbb5f11ab5cf828c12abf84c5b33db55.apk Binary XML file line #2062
09-02 12:38:10.804 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.qqpimsecure-6755.apk Binary XML file line #836
09-02 12:38:11.150 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.sohu.inputmethod.sogou1460.apk Binary XML file line #264
09-02 12:38:11.252 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.qqpimsecure-6790.apk Binary XML file line #834
09-02 12:38:11.406 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher2.permission.READ_SETTINGS in package: com.tencent.mobileqq at: Binary XML file line #81
09-02 12:38:11.406 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WRITE_CONTACTS in package: com.tencent.mobileqq at: Binary XML file line #112
09-02 12:38:11.413 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #183
09-02 12:38:11.413 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CHANGE_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #190
09-02 12:38:11.413 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.INTERNET in package: com.tencent.mobileqq at: Binary XML file line #191
09-02 12:38:11.413 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #192
09-02 12:38:11.413 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_NETWORK_STATE in package: com.tencent.mobileqq at: Binary XML file line #193
09-02 12:38:11.413 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CAMERA in package: com.tencent.mobileqq at: Binary XML file line #197
09-02 12:38:11.413 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.tencent.mobileqq at: Binary XML file line #198
09-02 12:38:11.413 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WAKE_LOCK in package: com.tencent.mobileqq at: Binary XML file line #199
09-02 12:38:11.413 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher.permission.INSTALL_SHORTCUT in package: com.tencent.mobileqq at: Binary XML file line #200
09-02 12:38:11.413 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.RECEIVE_BOOT_COMPLETED in package: com.tencent.mobileqq at: Binary XML file line #201
09-02 12:38:11.413 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #203
09-02 12:38:11.424 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.mobileqq1792.apk Binary XML file line #2077
09-02 12:38:11.578 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-02 12:38:11.579 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #75
09-02 12:38:11.590 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #1400
09-02 12:38:13.575 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-02 12:38:13.576 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #75
09-02 12:38:13.587 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #1400
09-02 13:47:01.809 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher2.permission.READ_SETTINGS in package: com.tencent.mobileqq at: Binary XML file line #83
09-02 13:47:01.809 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WRITE_CONTACTS in package: com.tencent.mobileqq at: Binary XML file line #114
09-02 13:47:01.810 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #185
09-02 13:47:01.810 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CHANGE_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #192
09-02 13:47:01.810 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.INTERNET in package: com.tencent.mobileqq at: Binary XML file line #193
09-02 13:47:01.810 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #194
09-02 13:47:01.810 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_NETWORK_STATE in package: com.tencent.mobileqq at: Binary XML file line #195
09-02 13:47:01.810 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CAMERA in package: com.tencent.mobileqq at: Binary XML file line #199
09-02 13:47:01.810 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.tencent.mobileqq at: Binary XML file line #200
09-02 13:47:01.810 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WAKE_LOCK in package: com.tencent.mobileqq at: Binary XML file line #201
09-02 13:47:01.810 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher.permission.INSTALL_SHORTCUT in package: com.tencent.mobileqq at: Binary XML file line #202
09-02 13:47:01.810 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.RECEIVE_BOOT_COMPLETED in package: com.tencent.mobileqq at: Binary XML file line #203
09-02 13:47:01.811 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #205
09-02 13:47:01.823 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Android/data/com.tencent.mobileqq/Tencent/TMAssistantSDK/Download/com.tencent.mobileqq/AndroidBBPJQQ_8.8.17.5770_537084958_bbb5f11ab5cf828c12abf84c5b33db55.apk Binary XML file line #2062
09-02 13:47:02.259 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-02 13:47:02.259 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #75
09-02 13:47:02.271 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #1400
09-02 13:47:02.461 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-02 13:47:02.462 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #75
09-02 13:47:02.490 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #1400
09-02 13:47:05.382 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.qqpimsecure-6755.apk Binary XML file line #836
09-02 13:47:05.622 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.sohu.inputmethod.sogou1460.apk Binary XML file line #264
09-02 13:47:05.712 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.qqpimsecure-6790.apk Binary XML file line #834
09-02 13:47:05.813 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher2.permission.READ_SETTINGS in package: com.tencent.mobileqq at: Binary XML file line #81
09-02 13:47:05.814 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WRITE_CONTACTS in package: com.tencent.mobileqq at: Binary XML file line #112
09-02 13:47:05.815 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #183
09-02 13:47:05.815 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CHANGE_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #190
09-02 13:47:05.815 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.INTERNET in package: com.tencent.mobileqq at: Binary XML file line #191
09-02 13:47:05.815 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #192
09-02 13:47:05.815 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_NETWORK_STATE in package: com.tencent.mobileqq at: Binary XML file line #193
09-02 13:47:05.816 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CAMERA in package: com.tencent.mobileqq at: Binary XML file line #197
09-02 13:47:05.816 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.tencent.mobileqq at: Binary XML file line #198
09-02 13:47:05.816 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WAKE_LOCK in package: com.tencent.mobileqq at: Binary XML file line #199
09-02 13:47:05.816 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher.permission.INSTALL_SHORTCUT in package: com.tencent.mobileqq at: Binary XML file line #200
09-02 13:47:05.816 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.RECEIVE_BOOT_COMPLETED in package: com.tencent.mobileqq at: Binary XML file line #201
09-02 13:47:05.816 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #203
09-02 13:47:05.827 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.mobileqq1792.apk Binary XML file line #2077
09-02 13:47:06.030 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-02 13:47:06.032 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #75
09-02 13:47:06.045 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #1400
09-02 13:47:08.375 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-02 13:47:08.376 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #75
09-02 13:47:08.387 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #1400
09-02 13:52:15.537 W/vold    (  228): Failed to read namespace for 6618: No such file or directory
09-02 13:52:15.538 W/vold    (  228): Failed to read namespace for 6619: No such file or directory
09-02 13:52:15.538 W/vold    (  228): Failed to read namespace for 6625: No such file or directory
09-02 13:52:15.551 W/vold    (  228): Failed to read namespace for 24433: No such file or directory
09-02 13:52:15.551 W/vold    (  228): Failed to read namespace for 24439: No such file or directory
09-02 13:52:15.551 W/vold    (  228): Failed to read namespace for 24472: No such file or directory
09-02 13:52:15.551 W/vold    (  228): Failed to read namespace for 24474: No such file or directory
09-02 13:52:15.551 W/vold    (  228): Failed to read namespace for 24479: No such file or directory
09-02 13:52:15.551 W/vold    (  228): Failed to read namespace for 24480: No such file or directory
09-02 13:52:15.554 W/vold    (  228): Failed to read namespace for 24536: No such file or directory
09-02 13:52:15.567 W/vold    (  228): Failed to read namespace for 6618: No such file or directory
09-02 13:52:15.567 W/vold    (  228): Failed to read namespace for 6619: No such file or directory
09-02 13:52:15.567 W/vold    (  228): Failed to read namespace for 6625: No such file or directory
09-02 13:52:15.584 W/vold    (  228): Failed to read namespace for 24433: No such file or directory
09-02 13:52:15.584 W/vold    (  228): Failed to read namespace for 24439: No such file or directory
09-02 13:52:15.584 W/vold    (  228): Failed to read namespace for 24472: No such file or directory
09-02 13:52:15.584 W/vold    (  228): Failed to read namespace for 24474: No such file or directory
09-02 13:52:15.585 W/vold    (  228): Failed to read namespace for 24479: No such file or directory
09-02 13:52:15.585 W/vold    (  228): Failed to read namespace for 24480: No such file or directory
09-02 13:52:15.587 W/vold    (  228): Failed to read namespace for 24536: No such file or directory
09-02 14:36:05.626 E/AndroidRuntime(16704): FATAL EXCEPTION: main
09-02 14:36:05.626 E/AndroidRuntime(16704): Process: com.tencent.qqpimsecure, PID: 16704
09-02 14:36:05.626 E/AndroidRuntime(16704): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 14:36:05.626 E/AndroidRuntime(16704): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	... 8 more
09-02 14:36:05.626 E/AndroidRuntime(16704): Caused by: java.lang.reflect.UndeclaredThrowableException
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at $Proxy5.init(Unknown Source)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	... 12 more
09-02 14:36:05.626 E/AndroidRuntime(16704): Caused by: java.lang.reflect.InvocationTargetException
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	... 16 more
09-02 14:36:05.626 E/AndroidRuntime(16704): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{194251 u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at epetrp.b.c(SourceFile:8)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	at epetrp.c.init(SourceFile:1)
09-02 14:36:05.626 E/AndroidRuntime(16704): 	... 19 more
09-02 14:36:10.633 E/AndroidRuntime(16704): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-02 14:36:10.633 E/AndroidRuntime(16704): Process: com.tencent.qqpimsecure, PID: 16704
09-02 14:36:10.633 E/AndroidRuntime(16704): java.lang.reflect.UndeclaredThrowableException
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at $Proxy6.getPreferenceService(Unknown Source)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at epmt.j.c(SourceFile:1)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at epmt.c.a(SourceFile:2)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at epmt.g.l(SourceFile:99)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at epmt.g.a(SourceFile:2)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at epmt.g$c.handleMessage(SourceFile:1)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at tcs.alk.run(SourceFile:79)
09-02 14:36:10.633 E/AndroidRuntime(16704): Caused by: java.lang.reflect.InvocationTargetException
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	... 10 more
09-02 14:36:10.633 E/AndroidRuntime(16704): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at java.lang.Thread.start(Thread.java:733)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at tcs.eiv.aq(SourceFile:111)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at tcs.ahr.<init>(SourceFile:16)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-02 14:36:10.633 E/AndroidRuntime(16704): 	... 13 more
09-02 14:36:10.648 E/AndroidRuntime(16704): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-02 14:36:10.648 E/AndroidRuntime(16704): Process: com.tencent.qqpimsecure, PID: 16704
09-02 14:36:10.648 E/AndroidRuntime(16704): java.lang.InternalError: Thread starting during runtime shutdown
09-02 14:36:10.648 E/AndroidRuntime(16704): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 14:36:10.648 E/AndroidRuntime(16704): 	at java.lang.Thread.start(Thread.java:733)
09-02 14:36:10.648 E/AndroidRuntime(16704): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 14:36:10.648 E/AndroidRuntime(16704): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 14:36:10.648 E/AndroidRuntime(16704): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 14:36:10.648 E/AndroidRuntime(16704): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 14:36:10.648 E/AndroidRuntime(16704): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 14:36:10.648 E/AndroidRuntime(16704): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 14:36:10.648 E/AndroidRuntime(16704): 	at tcs.bca.<init>(SourceFile:24)
09-02 14:36:10.648 E/AndroidRuntime(16704): 	at tcs.bcb.dv(SourceFile:157)
09-02 14:36:10.648 E/AndroidRuntime(16704): 	at tcs.bcb.b(SourceFile:135)
09-02 14:36:10.648 E/AndroidRuntime(16704): 	at tcs.bcb.uF(SourceFile:229)
09-02 14:36:10.648 E/AndroidRuntime(16704): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-02 14:36:10.648 E/AndroidRuntime(16704): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 14:36:10.648 E/AndroidRuntime(16704): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 14:36:10.648 E/AndroidRuntime(16704): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-02 14:36:10.648 E/AndroidRuntime(16704): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:36:10.648 E/AndroidRuntime(16704): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 14:36:10.648 E/AndroidRuntime(16704): 	at tcs.alk.run(SourceFile:79)
09-02 14:36:12.702 E/AndroidRuntime(16895): FATAL EXCEPTION: main
09-02 14:36:12.702 E/AndroidRuntime(16895): Process: com.tencent.qqpimsecure, PID: 16895
09-02 14:36:12.702 E/AndroidRuntime(16895): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 14:36:12.702 E/AndroidRuntime(16895): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	... 8 more
09-02 14:36:12.702 E/AndroidRuntime(16895): Caused by: java.lang.reflect.UndeclaredThrowableException
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at $Proxy5.init(Unknown Source)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	... 12 more
09-02 14:36:12.702 E/AndroidRuntime(16895): Caused by: java.lang.reflect.InvocationTargetException
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	... 16 more
09-02 14:36:12.702 E/AndroidRuntime(16895): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{1e1f0aa u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at epetrp.b.c(SourceFile:8)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	at epetrp.c.init(SourceFile:1)
09-02 14:36:12.702 E/AndroidRuntime(16895): 	... 19 more
09-02 14:36:17.684 E/AndroidRuntime(16895): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-02 14:36:17.684 E/AndroidRuntime(16895): Process: com.tencent.qqpimsecure, PID: 16895
09-02 14:36:17.684 E/AndroidRuntime(16895): java.lang.InternalError: Thread starting during runtime shutdown
09-02 14:36:17.684 E/AndroidRuntime(16895): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 14:36:17.684 E/AndroidRuntime(16895): 	at java.lang.Thread.start(Thread.java:733)
09-02 14:36:17.684 E/AndroidRuntime(16895): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 14:36:17.684 E/AndroidRuntime(16895): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 14:36:17.684 E/AndroidRuntime(16895): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 14:36:17.684 E/AndroidRuntime(16895): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 14:36:17.684 E/AndroidRuntime(16895): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 14:36:17.684 E/AndroidRuntime(16895): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 14:36:17.684 E/AndroidRuntime(16895): 	at tcs.bca.<init>(SourceFile:24)
09-02 14:36:17.684 E/AndroidRuntime(16895): 	at tcs.bcb.dv(SourceFile:157)
09-02 14:36:17.684 E/AndroidRuntime(16895): 	at tcs.bcb.b(SourceFile:135)
09-02 14:36:17.684 E/AndroidRuntime(16895): 	at tcs.bcb.uF(SourceFile:229)
09-02 14:36:17.684 E/AndroidRuntime(16895): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-02 14:36:17.684 E/AndroidRuntime(16895): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 14:36:17.684 E/AndroidRuntime(16895): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 14:36:17.684 E/AndroidRuntime(16895): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-02 14:36:17.684 E/AndroidRuntime(16895): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:36:17.684 E/AndroidRuntime(16895): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 14:36:17.684 E/AndroidRuntime(16895): 	at tcs.alk.run(SourceFile:79)
09-02 14:36:17.709 E/AndroidRuntime(16895): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-02 14:36:17.709 E/AndroidRuntime(16895): Process: com.tencent.qqpimsecure, PID: 16895
09-02 14:36:17.709 E/AndroidRuntime(16895): java.lang.reflect.UndeclaredThrowableException
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at $Proxy6.getPreferenceService(Unknown Source)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at epmt.j.c(SourceFile:1)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at epmt.c.a(SourceFile:2)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at epmt.g.l(SourceFile:99)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at epmt.g.a(SourceFile:2)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at epmt.g$c.handleMessage(SourceFile:1)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at tcs.alk.run(SourceFile:79)
09-02 14:36:17.709 E/AndroidRuntime(16895): Caused by: java.lang.reflect.InvocationTargetException
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	... 10 more
09-02 14:36:17.709 E/AndroidRuntime(16895): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at java.lang.Thread.start(Thread.java:733)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at tcs.eiv.aq(SourceFile:111)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at tcs.ahr.<init>(SourceFile:16)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-02 14:36:17.709 E/AndroidRuntime(16895): 	... 13 more
09-02 14:36:22.770 E/AndroidRuntime(17043): FATAL EXCEPTION: main
09-02 14:36:22.770 E/AndroidRuntime(17043): Process: com.tencent.qqpimsecure, PID: 17043
09-02 14:36:22.770 E/AndroidRuntime(17043): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 14:36:22.770 E/AndroidRuntime(17043): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	... 8 more
09-02 14:36:22.770 E/AndroidRuntime(17043): Caused by: java.lang.reflect.UndeclaredThrowableException
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at $Proxy5.init(Unknown Source)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	... 12 more
09-02 14:36:22.770 E/AndroidRuntime(17043): Caused by: java.lang.reflect.InvocationTargetException
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	... 16 more
09-02 14:36:22.770 E/AndroidRuntime(17043): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{dbf233f u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at epetrp.b.c(SourceFile:8)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	at epetrp.c.init(SourceFile:1)
09-02 14:36:22.770 E/AndroidRuntime(17043): 	... 19 more
09-02 14:36:27.748 E/AndroidRuntime(17043): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-02 14:36:27.748 E/AndroidRuntime(17043): Process: com.tencent.qqpimsecure, PID: 17043
09-02 14:36:27.748 E/AndroidRuntime(17043): java.lang.InternalError: Thread starting during runtime shutdown
09-02 14:36:27.748 E/AndroidRuntime(17043): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 14:36:27.748 E/AndroidRuntime(17043): 	at java.lang.Thread.start(Thread.java:733)
09-02 14:36:27.748 E/AndroidRuntime(17043): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 14:36:27.748 E/AndroidRuntime(17043): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 14:36:27.748 E/AndroidRuntime(17043): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 14:36:27.748 E/AndroidRuntime(17043): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 14:36:27.748 E/AndroidRuntime(17043): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 14:36:27.748 E/AndroidRuntime(17043): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 14:36:27.748 E/AndroidRuntime(17043): 	at tcs.bca.<init>(SourceFile:24)
09-02 14:36:27.748 E/AndroidRuntime(17043): 	at tcs.bcb.dv(SourceFile:157)
09-02 14:36:27.748 E/AndroidRuntime(17043): 	at tcs.bcb.b(SourceFile:135)
09-02 14:36:27.748 E/AndroidRuntime(17043): 	at tcs.bcb.uF(SourceFile:229)
09-02 14:36:27.748 E/AndroidRuntime(17043): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-02 14:36:27.748 E/AndroidRuntime(17043): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 14:36:27.748 E/AndroidRuntime(17043): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 14:36:27.748 E/AndroidRuntime(17043): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-02 14:36:27.748 E/AndroidRuntime(17043): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:36:27.748 E/AndroidRuntime(17043): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 14:36:27.748 E/AndroidRuntime(17043): 	at tcs.alk.run(SourceFile:79)
09-02 14:36:27.782 E/AndroidRuntime(17043): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-02 14:36:27.782 E/AndroidRuntime(17043): Process: com.tencent.qqpimsecure, PID: 17043
09-02 14:36:27.782 E/AndroidRuntime(17043): java.lang.reflect.UndeclaredThrowableException
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at $Proxy6.getPreferenceService(Unknown Source)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at epmt.j.c(SourceFile:1)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at epmt.c.a(SourceFile:2)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at epmt.g.l(SourceFile:99)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at epmt.g.a(SourceFile:2)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at epmt.g$c.handleMessage(SourceFile:1)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at tcs.alk.run(SourceFile:79)
09-02 14:36:27.782 E/AndroidRuntime(17043): Caused by: java.lang.reflect.InvocationTargetException
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	... 10 more
09-02 14:36:27.782 E/AndroidRuntime(17043): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at java.lang.Thread.start(Thread.java:733)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at tcs.eiv.aq(SourceFile:111)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at tcs.ahr.<init>(SourceFile:16)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-02 14:36:27.782 E/AndroidRuntime(17043): 	... 13 more
09-02 14:36:45.142 E/AndroidRuntime(17198): FATAL EXCEPTION: main
09-02 14:36:45.142 E/AndroidRuntime(17198): Process: com.tencent.qqpimsecure, PID: 17198
09-02 14:36:45.142 E/AndroidRuntime(17198): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 14:36:45.142 E/AndroidRuntime(17198): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	... 8 more
09-02 14:36:45.142 E/AndroidRuntime(17198): Caused by: java.lang.reflect.UndeclaredThrowableException
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at $Proxy6.init(Unknown Source)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	... 12 more
09-02 14:36:45.142 E/AndroidRuntime(17198): Caused by: java.lang.reflect.InvocationTargetException
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	... 16 more
09-02 14:36:45.142 E/AndroidRuntime(17198): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{f3816a0 u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at epetrp.b.c(SourceFile:8)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	at epetrp.c.init(SourceFile:1)
09-02 14:36:45.142 E/AndroidRuntime(17198): 	... 19 more
09-02 14:36:50.098 E/AndroidRuntime(17198): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-02 14:36:50.098 E/AndroidRuntime(17198): Process: com.tencent.qqpimsecure, PID: 17198
09-02 14:36:50.098 E/AndroidRuntime(17198): java.lang.InternalError: Thread starting during runtime shutdown
09-02 14:36:50.098 E/AndroidRuntime(17198): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 14:36:50.098 E/AndroidRuntime(17198): 	at java.lang.Thread.start(Thread.java:733)
09-02 14:36:50.098 E/AndroidRuntime(17198): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 14:36:50.098 E/AndroidRuntime(17198): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 14:36:50.098 E/AndroidRuntime(17198): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 14:36:50.098 E/AndroidRuntime(17198): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 14:36:50.098 E/AndroidRuntime(17198): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 14:36:50.098 E/AndroidRuntime(17198): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 14:36:50.098 E/AndroidRuntime(17198): 	at tcs.bca.<init>(SourceFile:24)
09-02 14:36:50.098 E/AndroidRuntime(17198): 	at tcs.bcb.dv(SourceFile:157)
09-02 14:36:50.098 E/AndroidRuntime(17198): 	at tcs.bcb.b(SourceFile:135)
09-02 14:36:50.098 E/AndroidRuntime(17198): 	at tcs.bcb.uF(SourceFile:229)
09-02 14:36:50.098 E/AndroidRuntime(17198): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-02 14:36:50.098 E/AndroidRuntime(17198): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 14:36:50.098 E/AndroidRuntime(17198): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 14:36:50.098 E/AndroidRuntime(17198): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-02 14:36:50.098 E/AndroidRuntime(17198): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:36:50.098 E/AndroidRuntime(17198): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 14:36:50.098 E/AndroidRuntime(17198): 	at tcs.alk.run(SourceFile:79)
09-02 14:36:50.143 E/AndroidRuntime(17198): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-02 14:36:50.143 E/AndroidRuntime(17198): Process: com.tencent.qqpimsecure, PID: 17198
09-02 14:36:50.143 E/AndroidRuntime(17198): java.lang.reflect.UndeclaredThrowableException
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at $Proxy5.getPreferenceService(Unknown Source)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at epmt.j.c(SourceFile:1)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at epmt.c.a(SourceFile:2)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at epmt.g.l(SourceFile:99)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at epmt.g.a(SourceFile:2)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at epmt.g$c.handleMessage(SourceFile:1)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at tcs.alk.run(SourceFile:79)
09-02 14:36:50.143 E/AndroidRuntime(17198): Caused by: java.lang.reflect.InvocationTargetException
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	... 10 more
09-02 14:36:50.143 E/AndroidRuntime(17198): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at java.lang.Thread.start(Thread.java:733)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at tcs.eiv.aq(SourceFile:111)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at tcs.ahr.<init>(SourceFile:16)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-02 14:36:50.143 E/AndroidRuntime(17198): 	... 13 more
09-02 14:37:55.110 E/AndroidRuntime(17375): FATAL EXCEPTION: main
09-02 14:37:55.110 E/AndroidRuntime(17375): Process: com.tencent.qqpimsecure, PID: 17375
09-02 14:37:55.110 E/AndroidRuntime(17375): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 14:37:55.110 E/AndroidRuntime(17375): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	... 8 more
09-02 14:37:55.110 E/AndroidRuntime(17375): Caused by: java.lang.reflect.UndeclaredThrowableException
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at $Proxy6.init(Unknown Source)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	... 12 more
09-02 14:37:55.110 E/AndroidRuntime(17375): Caused by: java.lang.reflect.InvocationTargetException
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	... 16 more
09-02 14:37:55.110 E/AndroidRuntime(17375): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{2c2c019 u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at epetrp.b.c(SourceFile:8)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	at epetrp.c.init(SourceFile:1)
09-02 14:37:55.110 E/AndroidRuntime(17375): 	... 19 more
09-02 14:38:00.088 E/AndroidRuntime(17375): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-02 14:38:00.088 E/AndroidRuntime(17375): Process: com.tencent.qqpimsecure, PID: 17375
09-02 14:38:00.088 E/AndroidRuntime(17375): java.lang.InternalError: Thread starting during runtime shutdown
09-02 14:38:00.088 E/AndroidRuntime(17375): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 14:38:00.088 E/AndroidRuntime(17375): 	at java.lang.Thread.start(Thread.java:733)
09-02 14:38:00.088 E/AndroidRuntime(17375): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 14:38:00.088 E/AndroidRuntime(17375): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 14:38:00.088 E/AndroidRuntime(17375): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 14:38:00.088 E/AndroidRuntime(17375): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 14:38:00.088 E/AndroidRuntime(17375): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 14:38:00.088 E/AndroidRuntime(17375): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 14:38:00.088 E/AndroidRuntime(17375): 	at tcs.bca.<init>(SourceFile:24)
09-02 14:38:00.088 E/AndroidRuntime(17375): 	at tcs.bcb.dv(SourceFile:157)
09-02 14:38:00.088 E/AndroidRuntime(17375): 	at tcs.bcb.b(SourceFile:135)
09-02 14:38:00.088 E/AndroidRuntime(17375): 	at tcs.bcb.uF(SourceFile:229)
09-02 14:38:00.088 E/AndroidRuntime(17375): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-02 14:38:00.088 E/AndroidRuntime(17375): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 14:38:00.088 E/AndroidRuntime(17375): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 14:38:00.088 E/AndroidRuntime(17375): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-02 14:38:00.088 E/AndroidRuntime(17375): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:38:00.088 E/AndroidRuntime(17375): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 14:38:00.088 E/AndroidRuntime(17375): 	at tcs.alk.run(SourceFile:79)
09-02 14:38:00.112 E/AndroidRuntime(17375): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-02 14:38:00.112 E/AndroidRuntime(17375): Process: com.tencent.qqpimsecure, PID: 17375
09-02 14:38:00.112 E/AndroidRuntime(17375): java.lang.reflect.UndeclaredThrowableException
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at $Proxy5.getPreferenceService(Unknown Source)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at epmt.j.c(SourceFile:1)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at epmt.c.a(SourceFile:2)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at epmt.g.l(SourceFile:99)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at epmt.g.a(SourceFile:2)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at epmt.g$c.handleMessage(SourceFile:1)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at tcs.alk.run(SourceFile:79)
09-02 14:38:00.112 E/AndroidRuntime(17375): Caused by: java.lang.reflect.InvocationTargetException
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	... 10 more
09-02 14:38:00.112 E/AndroidRuntime(17375): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at java.lang.Thread.nativeCreate(Native Method)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at java.lang.Thread.start(Thread.java:733)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at tcs.eiv.aq(SourceFile:111)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at tcs.ahr.<init>(SourceFile:16)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-02 14:38:00.112 E/AndroidRuntime(17375): 	... 13 more
09-02 14:43:26.229 W/ViewRootImpl[MainActivitys](24234): Dropping event due to no window focus: KeyEvent { action=ACTION_DOWN, keyCode=KEYCODE_BACK, scanCode=158, metaState=0, flags=0x48, repeatCount=0, eventTime=211097862, downTime=211097862, deviceId=5, source=0x101 }
09-02 14:43:26.229 W/ViewRootImpl[MainActivitys](24234): Cancelling event due to no window focus: KeyEvent { action=ACTION_UP, keyCode=KEYCODE_BACK, scanCode=158, metaState=0, flags=0x68, repeatCount=0, eventTime=211097917, downTime=211097862, deviceId=5, source=0x101 }
09-02 14:43:26.231 W/ViewRootImpl[MainActivitys](24234): Cancelling event due to no window focus: KeyEvent { action=ACTION_UP, keyCode=KEYCODE_BACK, scanCode=158, metaState=0, flags=0x68, repeatCount=0, eventTime=211097917, downTime=211097862, deviceId=5, source=0x101 }
09-02 14:45:28.937 E/AndroidRuntime(24234): FATAL EXCEPTION: main
09-02 14:45:28.937 E/AndroidRuntime(24234): Process: com.shinyv.cnr, PID: 24234
09-02 14:45:28.937 E/AndroidRuntime(24234): java.lang.ClassCastException: java.lang.Double cannot be cast to java.lang.String
09-02 14:45:28.937 E/AndroidRuntime(24234): 	at com.linker.xlyt.read.ui.activity.joker.recommend.RecommendationActivity.lambda$initViews$3$RecommendationActivity(RecommendationActivity.java:168)
09-02 14:45:28.937 E/AndroidRuntime(24234): 	at com.linker.xlyt.read.ui.activity.joker.recommend.-$$Lambda$RecommendationActivity$JTHr61gxwwH8FVHK94WrR2f0SNk.onChanged(Unknown Source:4)
09-02 14:45:28.937 E/AndroidRuntime(24234): 	at androidx.lifecycle.LiveData.considerNotify(LiveData.java:131)
09-02 14:45:28.937 E/AndroidRuntime(24234): 	at androidx.lifecycle.LiveData.dispatchingValue(LiveData.java:149)
09-02 14:45:28.937 E/AndroidRuntime(24234): 	at androidx.lifecycle.LiveData.setValue(LiveData.java:307)
09-02 14:45:28.937 E/AndroidRuntime(24234): 	at androidx.lifecycle.MutableLiveData.setValue(MutableLiveData.java:50)
09-02 14:45:28.937 E/AndroidRuntime(24234): 	at androidx.lifecycle.LiveData$1.run(LiveData.java:91)
09-02 14:45:28.937 E/AndroidRuntime(24234): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 14:45:28.937 E/AndroidRuntime(24234): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 14:45:28.937 E/AndroidRuntime(24234): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:45:28.937 E/AndroidRuntime(24234): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 14:45:28.937 E/AndroidRuntime(24234): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 14:45:28.937 E/AndroidRuntime(24234): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 14:45:28.937 E/AndroidRuntime(24234): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 14:45:31.626 W/FileUtils(19627): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:45:31.638 W/FileUtils(19627): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:45:31.645 W/FileUtils(19627): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:45:31.646 W/FileUtils(19627): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:45:31.998 W/FileUtils(19627): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:45:31.999 W/FileUtils(19627): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:45:32.007 W/FileUtils(19627): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:45:32.009 W/FileUtils(19627): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:45:41.670 W/FileUtils(19627): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:45:41.670 W/FileUtils(19627): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:45:41.754 W/FileUtils(19627): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:45:41.755 W/FileUtils(19627): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:45:53.434 E/AndroidRuntime(19627): FATAL EXCEPTION: main
09-02 14:45:53.434 E/AndroidRuntime(19627): Process: com.shinyv.cnr, PID: 19627
09-02 14:45:53.434 E/AndroidRuntime(19627): java.lang.ClassCastException: java.lang.Double cannot be cast to java.lang.String
09-02 14:45:53.434 E/AndroidRuntime(19627): 	at com.linker.xlyt.read.ui.activity.joker.recommend.RecommendationActivity.lambda$initViews$3$RecommendationActivity(RecommendationActivity.java:168)
09-02 14:45:53.434 E/AndroidRuntime(19627): 	at com.linker.xlyt.read.ui.activity.joker.recommend.-$$Lambda$RecommendationActivity$JTHr61gxwwH8FVHK94WrR2f0SNk.onChanged(Unknown Source:4)
09-02 14:45:53.434 E/AndroidRuntime(19627): 	at androidx.lifecycle.LiveData.considerNotify(LiveData.java:131)
09-02 14:45:53.434 E/AndroidRuntime(19627): 	at androidx.lifecycle.LiveData.dispatchingValue(LiveData.java:149)
09-02 14:45:53.434 E/AndroidRuntime(19627): 	at androidx.lifecycle.LiveData.setValue(LiveData.java:307)
09-02 14:45:53.434 E/AndroidRuntime(19627): 	at androidx.lifecycle.MutableLiveData.setValue(MutableLiveData.java:50)
09-02 14:45:53.434 E/AndroidRuntime(19627): 	at androidx.lifecycle.LiveData$1.run(LiveData.java:91)
09-02 14:45:53.434 E/AndroidRuntime(19627): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 14:45:53.434 E/AndroidRuntime(19627): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 14:45:53.434 E/AndroidRuntime(19627): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:45:53.434 E/AndroidRuntime(19627): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 14:45:53.434 E/AndroidRuntime(19627): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 14:45:53.434 E/AndroidRuntime(19627): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 14:45:53.434 E/AndroidRuntime(19627): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 14:45:55.755 W/FileUtils(20079): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:45:55.755 W/FileUtils(20079): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:45:55.776 W/FileUtils(20079): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:45:55.777 W/FileUtils(20079): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:46:14.049 E/AndroidRuntime(20079): FATAL EXCEPTION: main
09-02 14:46:14.049 E/AndroidRuntime(20079): Process: com.shinyv.cnr, PID: 20079
09-02 14:46:14.049 E/AndroidRuntime(20079): java.lang.ClassCastException: java.lang.Double cannot be cast to java.lang.String
09-02 14:46:14.049 E/AndroidRuntime(20079): 	at com.linker.xlyt.read.ui.activity.joker.recommend.RecommendationActivity.lambda$initViews$3$RecommendationActivity(RecommendationActivity.java:168)
09-02 14:46:14.049 E/AndroidRuntime(20079): 	at com.linker.xlyt.read.ui.activity.joker.recommend.-$$Lambda$RecommendationActivity$JTHr61gxwwH8FVHK94WrR2f0SNk.onChanged(Unknown Source:4)
09-02 14:46:14.049 E/AndroidRuntime(20079): 	at androidx.lifecycle.LiveData.considerNotify(LiveData.java:131)
09-02 14:46:14.049 E/AndroidRuntime(20079): 	at androidx.lifecycle.LiveData.dispatchingValue(LiveData.java:149)
09-02 14:46:14.049 E/AndroidRuntime(20079): 	at androidx.lifecycle.LiveData.setValue(LiveData.java:307)
09-02 14:46:14.049 E/AndroidRuntime(20079): 	at androidx.lifecycle.MutableLiveData.setValue(MutableLiveData.java:50)
09-02 14:46:14.049 E/AndroidRuntime(20079): 	at androidx.lifecycle.LiveData$1.run(LiveData.java:91)
09-02 14:46:14.049 E/AndroidRuntime(20079): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 14:46:14.049 E/AndroidRuntime(20079): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 14:46:14.049 E/AndroidRuntime(20079): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:46:14.049 E/AndroidRuntime(20079): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 14:46:14.049 E/AndroidRuntime(20079): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 14:46:14.049 E/AndroidRuntime(20079): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 14:46:14.049 E/AndroidRuntime(20079): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 14:46:22.325 W/ContextImpl(14525): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1556 android.content.ContextWrapper.bindService:684 android.content.pm.permission.RuntimePermissionPresenter$RemoteService.processMessage:171 android.content.pm.permission.RuntimePermissionPresenter.getAppPermissions:118 com.android.settingslib.applications.PermissionsSummaryHelper.getPermissionSummary:34 
09-02 14:46:34.703 W/FileUtils(20732): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:46:34.724 W/FileUtils(20732): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:46:34.729 W/FileUtils(20732): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:46:34.731 W/FileUtils(20732): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:46:35.039 W/FileUtils(20732): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:46:35.042 W/FileUtils(20732): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:46:35.063 W/PackageParser(20732): Failed to parse /storage/emulated/0/tencent/tbs/backup/com.tencent.mm/x5.tbs.org
09-02 14:46:35.063 W/PackageParser(20732): java.io.FileNotFoundException: AndroidManifest.xml
09-02 14:46:35.063 W/PackageParser(20732): 	at android.content.res.AssetManager.openXmlAssetNative(Native Method)
09-02 14:46:35.063 W/PackageParser(20732): 	at android.content.res.AssetManager.openXmlBlockAsset(AssetManager.java:560)
09-02 14:46:35.063 W/PackageParser(20732): 	at android.content.res.AssetManager.openXmlResourceParser(AssetManager.java:528)
09-02 14:46:35.063 W/PackageParser(20732): 	at android.content.pm.PackageParser.parseApkLite(PackageParser.java:1773)
09-02 14:46:35.063 W/PackageParser(20732): 	at android.content.pm.PackageParser.parseMonolithicPackageLite(PackageParser.java:906)
09-02 14:46:35.063 W/PackageParser(20732): 	at android.content.pm.PackageParser.parseMonolithicPackage(PackageParser.java:1294)
09-02 14:46:35.063 W/PackageParser(20732): 	at android.content.pm.PackageManager.getPackageArchiveInfo(PackageManager.java:4693)
09-02 14:46:35.063 W/PackageParser(20732): 	at com.tencent.smtt.utils.a.a(Unknown Source:146)
09-02 14:46:35.063 W/PackageParser(20732): 	at com.tencent.smtt.utils.a.a(Unknown Source:21)
09-02 14:46:35.063 W/PackageParser(20732): 	at com.tencent.smtt.sdk.TbsDownloader.a(Unknown Source:65)
09-02 14:46:35.063 W/PackageParser(20732): 	at com.tencent.smtt.sdk.l.a(Unknown Source:69)
09-02 14:46:35.063 W/PackageParser(20732): 	at com.tencent.smtt.sdk.TbsDownloader.a(Unknown Source:1731)
09-02 14:46:35.063 W/PackageParser(20732): 	at com.tencent.smtt.sdk.TbsDownloader.b(Unknown Source:913)
09-02 14:46:35.063 W/PackageParser(20732): 	at com.tencent.smtt.sdk.TbsDownloader.a(Unknown Source:0)
09-02 14:46:35.063 W/PackageParser(20732): 	at com.tencent.smtt.sdk.TbsDownloader$2.handleMessage(Unknown Source:164)
09-02 14:46:35.063 W/PackageParser(20732): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-02 14:46:35.063 W/PackageParser(20732): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:46:35.063 W/PackageParser(20732): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-02 14:46:35.304 W/FileUtils(20732): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:46:35.306 W/FileUtils(20732): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:46:35.315 W/FileUtils(20732): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:46:35.321 W/FileUtils(20732): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:46:38.408 E/ActivityThread(20982): Failed to find provider info for com.vivo.push.sdk.service.SystemPushConfig
09-02 14:47:31.549 E/AndroidRuntime(20732): FATAL EXCEPTION: main
09-02 14:47:31.549 E/AndroidRuntime(20732): Process: com.shinyv.cnr, PID: 20732
09-02 14:47:31.549 E/AndroidRuntime(20732): java.lang.ClassCastException: java.lang.Double cannot be cast to java.lang.String
09-02 14:47:31.549 E/AndroidRuntime(20732): 	at com.linker.xlyt.read.ui.activity.joker.recommend.RecommendationActivity.lambda$initViews$3$RecommendationActivity(RecommendationActivity.java:168)
09-02 14:47:31.549 E/AndroidRuntime(20732): 	at com.linker.xlyt.read.ui.activity.joker.recommend.-$$Lambda$RecommendationActivity$JTHr61gxwwH8FVHK94WrR2f0SNk.onChanged(Unknown Source:4)
09-02 14:47:31.549 E/AndroidRuntime(20732): 	at androidx.lifecycle.LiveData.considerNotify(LiveData.java:131)
09-02 14:47:31.549 E/AndroidRuntime(20732): 	at androidx.lifecycle.LiveData.dispatchingValue(LiveData.java:149)
09-02 14:47:31.549 E/AndroidRuntime(20732): 	at androidx.lifecycle.LiveData.setValue(LiveData.java:307)
09-02 14:47:31.549 E/AndroidRuntime(20732): 	at androidx.lifecycle.MutableLiveData.setValue(MutableLiveData.java:50)
09-02 14:47:31.549 E/AndroidRuntime(20732): 	at androidx.lifecycle.LiveData$1.run(LiveData.java:91)
09-02 14:47:31.549 E/AndroidRuntime(20732): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 14:47:31.549 E/AndroidRuntime(20732): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 14:47:31.549 E/AndroidRuntime(20732): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:47:31.549 E/AndroidRuntime(20732): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 14:47:31.549 E/AndroidRuntime(20732): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 14:47:31.549 E/AndroidRuntime(20732): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 14:47:31.549 E/AndroidRuntime(20732): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 14:47:33.885 W/FileUtils(21472): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:47:33.909 W/FileUtils(21472): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:47:33.914 W/FileUtils(21472): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:47:33.915 W/FileUtils(21472): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:48:15.888 E/AndroidRuntime(21472): FATAL EXCEPTION: main
09-02 14:48:15.888 E/AndroidRuntime(21472): Process: com.shinyv.cnr, PID: 21472
09-02 14:48:15.888 E/AndroidRuntime(21472): java.lang.ClassCastException: java.lang.Double cannot be cast to java.lang.String
09-02 14:48:15.888 E/AndroidRuntime(21472): 	at com.linker.xlyt.read.ui.activity.joker.recommend.RecommendationActivity.lambda$initViews$3$RecommendationActivity(RecommendationActivity.java:168)
09-02 14:48:15.888 E/AndroidRuntime(21472): 	at com.linker.xlyt.read.ui.activity.joker.recommend.-$$Lambda$RecommendationActivity$JTHr61gxwwH8FVHK94WrR2f0SNk.onChanged(Unknown Source:4)
09-02 14:48:15.888 E/AndroidRuntime(21472): 	at androidx.lifecycle.LiveData.considerNotify(LiveData.java:131)
09-02 14:48:15.888 E/AndroidRuntime(21472): 	at androidx.lifecycle.LiveData.dispatchingValue(LiveData.java:149)
09-02 14:48:15.888 E/AndroidRuntime(21472): 	at androidx.lifecycle.LiveData.setValue(LiveData.java:307)
09-02 14:48:15.888 E/AndroidRuntime(21472): 	at androidx.lifecycle.MutableLiveData.setValue(MutableLiveData.java:50)
09-02 14:48:15.888 E/AndroidRuntime(21472): 	at androidx.lifecycle.LiveData$1.run(LiveData.java:91)
09-02 14:48:15.888 E/AndroidRuntime(21472): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 14:48:15.888 E/AndroidRuntime(21472): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 14:48:15.888 E/AndroidRuntime(21472): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:48:15.888 E/AndroidRuntime(21472): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 14:48:15.888 E/AndroidRuntime(21472): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 14:48:15.888 E/AndroidRuntime(21472): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 14:48:15.888 E/AndroidRuntime(21472): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 14:48:17.687 W/FileUtils(22049): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:48:17.700 W/FileUtils(22049): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:48:17.706 W/FileUtils(22049): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:48:17.707 W/FileUtils(22049): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:48:37.625 E/AndroidRuntime(22049): FATAL EXCEPTION: main
09-02 14:48:37.625 E/AndroidRuntime(22049): Process: com.shinyv.cnr, PID: 22049
09-02 14:48:37.625 E/AndroidRuntime(22049): java.lang.ClassCastException: java.lang.Double cannot be cast to java.lang.String
09-02 14:48:37.625 E/AndroidRuntime(22049): 	at com.linker.xlyt.read.ui.activity.joker.recommend.RecommendationActivity.lambda$initViews$3$RecommendationActivity(RecommendationActivity.java:168)
09-02 14:48:37.625 E/AndroidRuntime(22049): 	at com.linker.xlyt.read.ui.activity.joker.recommend.-$$Lambda$RecommendationActivity$JTHr61gxwwH8FVHK94WrR2f0SNk.onChanged(Unknown Source:4)
09-02 14:48:37.625 E/AndroidRuntime(22049): 	at androidx.lifecycle.LiveData.considerNotify(LiveData.java:131)
09-02 14:48:37.625 E/AndroidRuntime(22049): 	at androidx.lifecycle.LiveData.dispatchingValue(LiveData.java:149)
09-02 14:48:37.625 E/AndroidRuntime(22049): 	at androidx.lifecycle.LiveData.setValue(LiveData.java:307)
09-02 14:48:37.625 E/AndroidRuntime(22049): 	at androidx.lifecycle.MutableLiveData.setValue(MutableLiveData.java:50)
09-02 14:48:37.625 E/AndroidRuntime(22049): 	at androidx.lifecycle.LiveData$1.run(LiveData.java:91)
09-02 14:48:37.625 E/AndroidRuntime(22049): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 14:48:37.625 E/AndroidRuntime(22049): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 14:48:37.625 E/AndroidRuntime(22049): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:48:37.625 E/AndroidRuntime(22049): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 14:48:37.625 E/AndroidRuntime(22049): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 14:48:37.625 E/AndroidRuntime(22049): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 14:48:37.625 E/AndroidRuntime(22049): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 14:48:39.876 W/FileUtils(22369): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:48:39.898 W/FileUtils(22369): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:48:39.905 W/FileUtils(22369): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:48:39.906 W/FileUtils(22369): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:49:56.068 W/vold    (  228): Failed to read namespace for 21010: No such file or directory
09-02 14:49:56.074 W/vold    (  228): Failed to read namespace for 21836: No such file or directory
09-02 14:49:56.091 W/vold    (  228): Failed to read namespace for 22432: No such file or directory
09-02 14:49:56.092 W/vold    (  228): Failed to read namespace for 22453: No such file or directory
09-02 14:49:56.092 W/vold    (  228): Failed to read namespace for 22460: No such file or directory
09-02 14:49:56.114 W/vold    (  228): Failed to read namespace for 21010: No such file or directory
09-02 14:49:56.124 W/vold    (  228): Failed to read namespace for 21836: No such file or directory
09-02 14:49:56.132 W/vold    (  228): Failed to read namespace for 22432: No such file or directory
09-02 14:49:56.132 W/vold    (  228): Failed to read namespace for 22453: No such file or directory
09-02 14:49:56.132 W/vold    (  228): Failed to read namespace for 22460: No such file or directory
09-02 14:51:08.278 E/AndroidRuntime(22369): FATAL EXCEPTION: main
09-02 14:51:08.278 E/AndroidRuntime(22369): Process: com.shinyv.cnr, PID: 22369
09-02 14:51:08.278 E/AndroidRuntime(22369): java.lang.ClassCastException: java.lang.Double cannot be cast to java.lang.String
09-02 14:51:08.278 E/AndroidRuntime(22369): 	at com.linker.xlyt.read.ui.activity.joker.recommend.RecommendationActivity.lambda$initViews$3$RecommendationActivity(RecommendationActivity.java:168)
09-02 14:51:08.278 E/AndroidRuntime(22369): 	at com.linker.xlyt.read.ui.activity.joker.recommend.-$$Lambda$RecommendationActivity$JTHr61gxwwH8FVHK94WrR2f0SNk.onChanged(Unknown Source:4)
09-02 14:51:08.278 E/AndroidRuntime(22369): 	at androidx.lifecycle.LiveData.considerNotify(LiveData.java:131)
09-02 14:51:08.278 E/AndroidRuntime(22369): 	at androidx.lifecycle.LiveData.dispatchingValue(LiveData.java:149)
09-02 14:51:08.278 E/AndroidRuntime(22369): 	at androidx.lifecycle.LiveData.setValue(LiveData.java:307)
09-02 14:51:08.278 E/AndroidRuntime(22369): 	at androidx.lifecycle.MutableLiveData.setValue(MutableLiveData.java:50)
09-02 14:51:08.278 E/AndroidRuntime(22369): 	at androidx.lifecycle.LiveData$1.run(LiveData.java:91)
09-02 14:51:08.278 E/AndroidRuntime(22369): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 14:51:08.278 E/AndroidRuntime(22369): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 14:51:08.278 E/AndroidRuntime(22369): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:51:08.278 E/AndroidRuntime(22369): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 14:51:08.278 E/AndroidRuntime(22369): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 14:51:08.278 E/AndroidRuntime(22369): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 14:51:08.278 E/AndroidRuntime(22369): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 14:51:10.075 W/FileUtils(23398): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:51:10.083 W/FileUtils(23398): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:51:10.090 W/FileUtils(23398): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:51:10.092 W/FileUtils(23398): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:51:10.186 W/FileUtils(23398): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:51:10.188 W/FileUtils(23398): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:51:10.192 W/FileUtils(23398): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:51:10.193 W/FileUtils(23398): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:51:10.428 W/FileUtils(23398): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:51:10.430 W/FileUtils(23398): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:51:10.443 W/FileUtils(23398): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:51:10.445 W/FileUtils(23398): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:51:20.847 W/FileUtils(23398): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:51:20.848 W/FileUtils(23398): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:51:20.913 W/FileUtils(23398): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:51:20.917 W/FileUtils(23398): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:51:25.020 E/AndroidRuntime(23398): FATAL EXCEPTION: main
09-02 14:51:25.020 E/AndroidRuntime(23398): Process: com.shinyv.cnr, PID: 23398
09-02 14:51:25.020 E/AndroidRuntime(23398): java.lang.ClassCastException: java.lang.Double cannot be cast to java.lang.String
09-02 14:51:25.020 E/AndroidRuntime(23398): 	at com.linker.xlyt.read.ui.activity.joker.recommend.RecommendationActivity.lambda$initViews$3$RecommendationActivity(RecommendationActivity.java:168)
09-02 14:51:25.020 E/AndroidRuntime(23398): 	at com.linker.xlyt.read.ui.activity.joker.recommend.-$$Lambda$RecommendationActivity$JTHr61gxwwH8FVHK94WrR2f0SNk.onChanged(Unknown Source:4)
09-02 14:51:25.020 E/AndroidRuntime(23398): 	at androidx.lifecycle.LiveData.considerNotify(LiveData.java:131)
09-02 14:51:25.020 E/AndroidRuntime(23398): 	at androidx.lifecycle.LiveData.dispatchingValue(LiveData.java:149)
09-02 14:51:25.020 E/AndroidRuntime(23398): 	at androidx.lifecycle.LiveData.setValue(LiveData.java:307)
09-02 14:51:25.020 E/AndroidRuntime(23398): 	at androidx.lifecycle.MutableLiveData.setValue(MutableLiveData.java:50)
09-02 14:51:25.020 E/AndroidRuntime(23398): 	at androidx.lifecycle.LiveData$1.run(LiveData.java:91)
09-02 14:51:25.020 E/AndroidRuntime(23398): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 14:51:25.020 E/AndroidRuntime(23398): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 14:51:25.020 E/AndroidRuntime(23398): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:51:25.020 E/AndroidRuntime(23398): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 14:51:25.020 E/AndroidRuntime(23398): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 14:51:25.020 E/AndroidRuntime(23398): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 14:51:25.020 E/AndroidRuntime(23398): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 14:51:30.139 W/FileUtils(23834): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:51:30.140 W/FileUtils(23834): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:51:30.148 W/FileUtils(23834): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:51:30.149 W/FileUtils(23834): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:54:03.889 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher2.permission.READ_SETTINGS in package: com.tencent.mobileqq at: Binary XML file line #83
09-02 14:54:03.889 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WRITE_CONTACTS in package: com.tencent.mobileqq at: Binary XML file line #114
09-02 14:54:03.897 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #185
09-02 14:54:03.897 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CHANGE_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #192
09-02 14:54:03.897 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.INTERNET in package: com.tencent.mobileqq at: Binary XML file line #193
09-02 14:54:03.897 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #194
09-02 14:54:03.898 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_NETWORK_STATE in package: com.tencent.mobileqq at: Binary XML file line #195
09-02 14:54:03.898 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CAMERA in package: com.tencent.mobileqq at: Binary XML file line #199
09-02 14:54:03.898 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.tencent.mobileqq at: Binary XML file line #200
09-02 14:54:03.898 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WAKE_LOCK in package: com.tencent.mobileqq at: Binary XML file line #201
09-02 14:54:03.898 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher.permission.INSTALL_SHORTCUT in package: com.tencent.mobileqq at: Binary XML file line #202
09-02 14:54:03.898 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.RECEIVE_BOOT_COMPLETED in package: com.tencent.mobileqq at: Binary XML file line #203
09-02 14:54:03.898 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #205
09-02 14:54:03.909 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Android/data/com.tencent.mobileqq/Tencent/TMAssistantSDK/Download/com.tencent.mobileqq/AndroidBBPJQQ_8.8.17.5770_537084958_bbb5f11ab5cf828c12abf84c5b33db55.apk Binary XML file line #2062
09-02 14:54:07.098 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.qqpimsecure-6755.apk Binary XML file line #836
09-02 14:54:07.324 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.sohu.inputmethod.sogou1460.apk Binary XML file line #264
09-02 14:54:07.411 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.qqpimsecure-6790.apk Binary XML file line #834
09-02 14:54:07.507 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher2.permission.READ_SETTINGS in package: com.tencent.mobileqq at: Binary XML file line #81
09-02 14:54:07.508 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WRITE_CONTACTS in package: com.tencent.mobileqq at: Binary XML file line #112
09-02 14:54:07.509 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #183
09-02 14:54:07.509 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CHANGE_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #190
09-02 14:54:07.509 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.INTERNET in package: com.tencent.mobileqq at: Binary XML file line #191
09-02 14:54:07.509 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #192
09-02 14:54:07.509 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_NETWORK_STATE in package: com.tencent.mobileqq at: Binary XML file line #193
09-02 14:54:07.509 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CAMERA in package: com.tencent.mobileqq at: Binary XML file line #197
09-02 14:54:07.509 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.tencent.mobileqq at: Binary XML file line #198
09-02 14:54:07.509 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WAKE_LOCK in package: com.tencent.mobileqq at: Binary XML file line #199
09-02 14:54:07.509 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher.permission.INSTALL_SHORTCUT in package: com.tencent.mobileqq at: Binary XML file line #200
09-02 14:54:07.509 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.RECEIVE_BOOT_COMPLETED in package: com.tencent.mobileqq at: Binary XML file line #201
09-02 14:54:07.509 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #203
09-02 14:54:07.521 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.mobileqq1792.apk Binary XML file line #2077
09-02 14:54:07.693 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-02 14:54:07.694 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #75
09-02 14:54:07.710 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #1400
09-02 14:54:09.958 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-02 14:54:09.959 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #75
09-02 14:54:09.970 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #1400
09-02 14:55:01.055 E/AndroidRuntime(23834): FATAL EXCEPTION: main
09-02 14:55:01.055 E/AndroidRuntime(23834): Process: com.shinyv.cnr, PID: 23834
09-02 14:55:01.055 E/AndroidRuntime(23834): java.lang.ClassCastException: java.lang.Double cannot be cast to java.lang.String
09-02 14:55:01.055 E/AndroidRuntime(23834): 	at com.linker.xlyt.read.ui.activity.joker.recommend.RecommendationActivity.lambda$initViews$3$RecommendationActivity(RecommendationActivity.java:168)
09-02 14:55:01.055 E/AndroidRuntime(23834): 	at com.linker.xlyt.read.ui.activity.joker.recommend.-$$Lambda$RecommendationActivity$JTHr61gxwwH8FVHK94WrR2f0SNk.onChanged(Unknown Source:4)
09-02 14:55:01.055 E/AndroidRuntime(23834): 	at androidx.lifecycle.LiveData.considerNotify(LiveData.java:131)
09-02 14:55:01.055 E/AndroidRuntime(23834): 	at androidx.lifecycle.LiveData.dispatchingValue(LiveData.java:149)
09-02 14:55:01.055 E/AndroidRuntime(23834): 	at androidx.lifecycle.LiveData.setValue(LiveData.java:307)
09-02 14:55:01.055 E/AndroidRuntime(23834): 	at androidx.lifecycle.MutableLiveData.setValue(MutableLiveData.java:50)
09-02 14:55:01.055 E/AndroidRuntime(23834): 	at androidx.lifecycle.LiveData$1.run(LiveData.java:91)
09-02 14:55:01.055 E/AndroidRuntime(23834): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 14:55:01.055 E/AndroidRuntime(23834): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 14:55:01.055 E/AndroidRuntime(23834): 	at android.os.Looper.loop(Looper.java:164)
09-02 14:55:01.055 E/AndroidRuntime(23834): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 14:55:01.055 E/AndroidRuntime(23834): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 14:55:01.055 E/AndroidRuntime(23834): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 14:55:01.055 E/AndroidRuntime(23834): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 14:55:03.227 W/FileUtils(24716): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:55:03.229 W/FileUtils(24716): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:55:03.244 W/FileUtils(24716): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 14:55:03.245 W/FileUtils(24716): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 15:28:40.400 E/AndroidRuntime(24716): FATAL EXCEPTION: main
09-02 15:28:40.400 E/AndroidRuntime(24716): Process: com.shinyv.cnr, PID: 24716
09-02 15:28:40.400 E/AndroidRuntime(24716): java.lang.ClassCastException: java.lang.Double cannot be cast to java.lang.String
09-02 15:28:40.400 E/AndroidRuntime(24716): 	at com.linker.xlyt.read.ui.activity.joker.recommend.RecommendationActivity.lambda$initViews$3$RecommendationActivity(RecommendationActivity.java:168)
09-02 15:28:40.400 E/AndroidRuntime(24716): 	at com.linker.xlyt.read.ui.activity.joker.recommend.-$$Lambda$RecommendationActivity$JTHr61gxwwH8FVHK94WrR2f0SNk.onChanged(Unknown Source:4)
09-02 15:28:40.400 E/AndroidRuntime(24716): 	at androidx.lifecycle.LiveData.considerNotify(LiveData.java:131)
09-02 15:28:40.400 E/AndroidRuntime(24716): 	at androidx.lifecycle.LiveData.dispatchingValue(LiveData.java:149)
09-02 15:28:40.400 E/AndroidRuntime(24716): 	at androidx.lifecycle.LiveData.setValue(LiveData.java:307)
09-02 15:28:40.400 E/AndroidRuntime(24716): 	at androidx.lifecycle.MutableLiveData.setValue(MutableLiveData.java:50)
09-02 15:28:40.400 E/AndroidRuntime(24716): 	at androidx.lifecycle.LiveData$1.run(LiveData.java:91)
09-02 15:28:40.400 E/AndroidRuntime(24716): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 15:28:40.400 E/AndroidRuntime(24716): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 15:28:40.400 E/AndroidRuntime(24716): 	at android.os.Looper.loop(Looper.java:164)
09-02 15:28:40.400 E/AndroidRuntime(24716): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 15:28:40.400 E/AndroidRuntime(24716): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 15:28:40.400 E/AndroidRuntime(24716): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 15:28:40.400 E/AndroidRuntime(24716): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 15:28:42.480 W/FileUtils(30183): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 15:28:42.480 W/FileUtils(30183): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 15:28:42.495 W/FileUtils(30183): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 15:28:42.498 W/FileUtils(30183): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 15:59:38.803 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher2.permission.READ_SETTINGS in package: com.tencent.mobileqq at: Binary XML file line #83
09-02 15:59:38.803 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WRITE_CONTACTS in package: com.tencent.mobileqq at: Binary XML file line #114
09-02 15:59:38.804 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #185
09-02 15:59:38.804 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CHANGE_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #192
09-02 15:59:38.804 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.INTERNET in package: com.tencent.mobileqq at: Binary XML file line #193
09-02 15:59:38.804 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #194
09-02 15:59:38.804 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_NETWORK_STATE in package: com.tencent.mobileqq at: Binary XML file line #195
09-02 15:59:38.805 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CAMERA in package: com.tencent.mobileqq at: Binary XML file line #199
09-02 15:59:38.805 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.tencent.mobileqq at: Binary XML file line #200
09-02 15:59:38.805 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WAKE_LOCK in package: com.tencent.mobileqq at: Binary XML file line #201
09-02 15:59:38.805 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher.permission.INSTALL_SHORTCUT in package: com.tencent.mobileqq at: Binary XML file line #202
09-02 15:59:38.805 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.RECEIVE_BOOT_COMPLETED in package: com.tencent.mobileqq at: Binary XML file line #203
09-02 15:59:38.805 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #205
09-02 15:59:38.820 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Android/data/com.tencent.mobileqq/Tencent/TMAssistantSDK/Download/com.tencent.mobileqq/AndroidBBPJQQ_8.8.17.5770_537084958_bbb5f11ab5cf828c12abf84c5b33db55.apk Binary XML file line #2062
09-02 15:59:41.601 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.qqpimsecure-6755.apk Binary XML file line #836
09-02 15:59:41.817 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.sohu.inputmethod.sogou1460.apk Binary XML file line #264
09-02 15:59:41.899 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.qqpimsecure-6790.apk Binary XML file line #834
09-02 15:59:41.984 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher2.permission.READ_SETTINGS in package: com.tencent.mobileqq at: Binary XML file line #81
09-02 15:59:41.985 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WRITE_CONTACTS in package: com.tencent.mobileqq at: Binary XML file line #112
09-02 15:59:41.985 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #183
09-02 15:59:41.986 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CHANGE_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #190
09-02 15:59:41.986 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.INTERNET in package: com.tencent.mobileqq at: Binary XML file line #191
09-02 15:59:41.986 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #192
09-02 15:59:41.986 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_NETWORK_STATE in package: com.tencent.mobileqq at: Binary XML file line #193
09-02 15:59:41.986 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CAMERA in package: com.tencent.mobileqq at: Binary XML file line #197
09-02 15:59:41.986 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.tencent.mobileqq at: Binary XML file line #198
09-02 15:59:41.986 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WAKE_LOCK in package: com.tencent.mobileqq at: Binary XML file line #199
09-02 15:59:41.986 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher.permission.INSTALL_SHORTCUT in package: com.tencent.mobileqq at: Binary XML file line #200
09-02 15:59:41.986 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.RECEIVE_BOOT_COMPLETED in package: com.tencent.mobileqq at: Binary XML file line #201
09-02 15:59:41.986 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #203
09-02 15:59:41.999 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.mobileqq1792.apk Binary XML file line #2077
09-02 15:59:42.152 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-02 15:59:42.153 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #75
09-02 15:59:42.162 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #1400
09-02 15:59:44.377 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-02 15:59:44.378 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #75
09-02 15:59:44.388 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #1400
09-02 16:05:44.650 E/AndroidRuntime(30183): FATAL EXCEPTION: main
09-02 16:05:44.650 E/AndroidRuntime(30183): Process: com.shinyv.cnr, PID: 30183
09-02 16:05:44.650 E/AndroidRuntime(30183): java.lang.ClassCastException: java.lang.Double cannot be cast to java.lang.String
09-02 16:05:44.650 E/AndroidRuntime(30183): 	at com.linker.xlyt.read.ui.activity.joker.recommend.RecommendationActivity.lambda$initViews$3$RecommendationActivity(RecommendationActivity.java:168)
09-02 16:05:44.650 E/AndroidRuntime(30183): 	at com.linker.xlyt.read.ui.activity.joker.recommend.-$$Lambda$RecommendationActivity$JTHr61gxwwH8FVHK94WrR2f0SNk.onChanged(Unknown Source:4)
09-02 16:05:44.650 E/AndroidRuntime(30183): 	at androidx.lifecycle.LiveData.considerNotify(LiveData.java:131)
09-02 16:05:44.650 E/AndroidRuntime(30183): 	at androidx.lifecycle.LiveData.dispatchingValue(LiveData.java:149)
09-02 16:05:44.650 E/AndroidRuntime(30183): 	at androidx.lifecycle.LiveData.setValue(LiveData.java:307)
09-02 16:05:44.650 E/AndroidRuntime(30183): 	at androidx.lifecycle.MutableLiveData.setValue(MutableLiveData.java:50)
09-02 16:05:44.650 E/AndroidRuntime(30183): 	at androidx.lifecycle.LiveData$1.run(LiveData.java:91)
09-02 16:05:44.650 E/AndroidRuntime(30183): 	at android.os.Handler.handleCallback(Handler.java:790)
09-02 16:05:44.650 E/AndroidRuntime(30183): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-02 16:05:44.650 E/AndroidRuntime(30183): 	at android.os.Looper.loop(Looper.java:164)
09-02 16:05:44.650 E/AndroidRuntime(30183): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-02 16:05:44.650 E/AndroidRuntime(30183): 	at java.lang.reflect.Method.invoke(Native Method)
09-02 16:05:44.650 E/AndroidRuntime(30183): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-02 16:05:44.650 E/AndroidRuntime(30183): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-02 16:05:47.034 W/FileUtils( 2850): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 16:05:47.034 W/FileUtils( 2850): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 16:05:47.100 W/FileUtils( 2850): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 16:05:47.101 W/FileUtils( 2850): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 16:09:13.809 W/FileUtils( 5812): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 16:09:13.811 W/FileUtils( 5812): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 16:09:13.830 W/FileUtils( 5812): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-02 16:09:13.831 W/FileUtils( 5812): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 00:17:59.950 E/ActivityThread( 3253): Failed to find provider info for com.android.badge
09-03 00:17:59.981 E/ActivityThread( 3253): Failed to find provider info for com.android.badge
09-03 05:53:58.417 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher2.permission.READ_SETTINGS in package: com.tencent.mobileqq at: Binary XML file line #83
09-03 05:53:58.418 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WRITE_CONTACTS in package: com.tencent.mobileqq at: Binary XML file line #114
09-03 05:53:58.419 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #185
09-03 05:53:58.419 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CHANGE_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #192
09-03 05:53:58.419 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.INTERNET in package: com.tencent.mobileqq at: Binary XML file line #193
09-03 05:53:58.419 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #194
09-03 05:53:58.419 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_NETWORK_STATE in package: com.tencent.mobileqq at: Binary XML file line #195
09-03 05:53:58.419 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CAMERA in package: com.tencent.mobileqq at: Binary XML file line #199
09-03 05:53:58.419 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.tencent.mobileqq at: Binary XML file line #200
09-03 05:53:58.419 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WAKE_LOCK in package: com.tencent.mobileqq at: Binary XML file line #201
09-03 05:53:58.419 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher.permission.INSTALL_SHORTCUT in package: com.tencent.mobileqq at: Binary XML file line #202
09-03 05:53:58.419 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.RECEIVE_BOOT_COMPLETED in package: com.tencent.mobileqq at: Binary XML file line #203
09-03 05:53:58.419 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #205
09-03 05:53:58.441 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Android/data/com.tencent.mobileqq/Tencent/TMAssistantSDK/Download/com.tencent.mobileqq/AndroidBBPJQQ_8.8.17.5770_537084958_bbb5f11ab5cf828c12abf84c5b33db55.apk Binary XML file line #2062
09-03 05:54:01.437 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.qqpimsecure-6755.apk Binary XML file line #836
09-03 05:54:01.682 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.sohu.inputmethod.sogou1460.apk Binary XML file line #264
09-03 05:54:01.760 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.qqpimsecure-6790.apk Binary XML file line #834
09-03 05:54:01.841 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher2.permission.READ_SETTINGS in package: com.tencent.mobileqq at: Binary XML file line #81
09-03 05:54:01.842 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WRITE_CONTACTS in package: com.tencent.mobileqq at: Binary XML file line #112
09-03 05:54:01.843 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #183
09-03 05:54:01.843 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CHANGE_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #190
09-03 05:54:01.843 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.INTERNET in package: com.tencent.mobileqq at: Binary XML file line #191
09-03 05:54:01.843 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #192
09-03 05:54:01.843 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_NETWORK_STATE in package: com.tencent.mobileqq at: Binary XML file line #193
09-03 05:54:01.843 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CAMERA in package: com.tencent.mobileqq at: Binary XML file line #197
09-03 05:54:01.843 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.tencent.mobileqq at: Binary XML file line #198
09-03 05:54:01.843 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WAKE_LOCK in package: com.tencent.mobileqq at: Binary XML file line #199
09-03 05:54:01.843 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher.permission.INSTALL_SHORTCUT in package: com.tencent.mobileqq at: Binary XML file line #200
09-03 05:54:01.843 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.RECEIVE_BOOT_COMPLETED in package: com.tencent.mobileqq at: Binary XML file line #201
09-03 05:54:01.843 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #203
09-03 05:54:01.853 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.mobileqq1792.apk Binary XML file line #2077
09-03 05:54:01.987 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-03 05:54:01.988 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #75
09-03 05:54:01.997 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #1400
09-03 05:54:04.299 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-03 05:54:04.300 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #75
09-03 05:54:04.309 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #1400
09-03 09:21:26.526 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher2.permission.READ_SETTINGS in package: com.tencent.mobileqq at: Binary XML file line #83
09-03 09:21:26.527 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WRITE_CONTACTS in package: com.tencent.mobileqq at: Binary XML file line #114
09-03 09:21:26.528 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #185
09-03 09:21:26.528 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CHANGE_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #192
09-03 09:21:26.528 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.INTERNET in package: com.tencent.mobileqq at: Binary XML file line #193
09-03 09:21:26.528 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #194
09-03 09:21:26.528 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_NETWORK_STATE in package: com.tencent.mobileqq at: Binary XML file line #195
09-03 09:21:26.528 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CAMERA in package: com.tencent.mobileqq at: Binary XML file line #199
09-03 09:21:26.528 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.tencent.mobileqq at: Binary XML file line #200
09-03 09:21:26.528 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WAKE_LOCK in package: com.tencent.mobileqq at: Binary XML file line #201
09-03 09:21:26.528 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher.permission.INSTALL_SHORTCUT in package: com.tencent.mobileqq at: Binary XML file line #202
09-03 09:21:26.528 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.RECEIVE_BOOT_COMPLETED in package: com.tencent.mobileqq at: Binary XML file line #203
09-03 09:21:26.528 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #205
09-03 09:21:26.545 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Android/data/com.tencent.mobileqq/Tencent/TMAssistantSDK/Download/com.tencent.mobileqq/AndroidBBPJQQ_8.8.17.5770_537084958_bbb5f11ab5cf828c12abf84c5b33db55.apk Binary XML file line #2062
09-03 09:21:27.976 E/AndroidRuntime( 1722): FATAL EXCEPTION: main
09-03 09:21:27.976 E/AndroidRuntime( 1722): Process: com.tencent.qqpimsecure, PID: 1722
09-03 09:21:27.976 E/AndroidRuntime( 1722): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at android.os.Looper.loop(Looper.java:164)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-03 09:21:27.976 E/AndroidRuntime( 1722): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	... 8 more
09-03 09:21:27.976 E/AndroidRuntime( 1722): Caused by: java.lang.reflect.UndeclaredThrowableException
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at $Proxy6.init(Unknown Source)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	... 12 more
09-03 09:21:27.976 E/AndroidRuntime( 1722): Caused by: java.lang.reflect.InvocationTargetException
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	... 16 more
09-03 09:21:27.976 E/AndroidRuntime( 1722): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{1847e94 u0a77 TRNB idle change:uncached procs:1 seq(0,0,0)}
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at epetrp.b.c(SourceFile:8)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	at epetrp.c.init(SourceFile:1)
09-03 09:21:27.976 E/AndroidRuntime( 1722): 	... 19 more
09-03 09:21:29.410 E/ActivityThread( 3253): Failed to find provider info for com.android.badge
09-03 09:21:32.317 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.qqpimsecure-6755.apk Binary XML file line #836
09-03 09:21:32.622 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.sohu.inputmethod.sogou1460.apk Binary XML file line #264
09-03 09:21:32.712 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.qqpimsecure-6790.apk Binary XML file line #834
09-03 09:21:32.810 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher2.permission.READ_SETTINGS in package: com.tencent.mobileqq at: Binary XML file line #81
09-03 09:21:32.811 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WRITE_CONTACTS in package: com.tencent.mobileqq at: Binary XML file line #112
09-03 09:21:32.812 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #183
09-03 09:21:32.812 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CHANGE_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #190
09-03 09:21:32.812 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.INTERNET in package: com.tencent.mobileqq at: Binary XML file line #191
09-03 09:21:32.812 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #192
09-03 09:21:32.812 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_NETWORK_STATE in package: com.tencent.mobileqq at: Binary XML file line #193
09-03 09:21:32.812 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CAMERA in package: com.tencent.mobileqq at: Binary XML file line #197
09-03 09:21:32.812 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.tencent.mobileqq at: Binary XML file line #198
09-03 09:21:32.812 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WAKE_LOCK in package: com.tencent.mobileqq at: Binary XML file line #199
09-03 09:21:32.812 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher.permission.INSTALL_SHORTCUT in package: com.tencent.mobileqq at: Binary XML file line #200
09-03 09:21:32.812 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.RECEIVE_BOOT_COMPLETED in package: com.tencent.mobileqq at: Binary XML file line #201
09-03 09:21:32.812 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #203
09-03 09:21:32.828 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.mobileqq1792.apk Binary XML file line #2077
09-03 09:21:32.843 E/AndroidRuntime( 1722): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-03 09:21:32.843 E/AndroidRuntime( 1722): Process: com.tencent.qqpimsecure, PID: 1722
09-03 09:21:32.843 E/AndroidRuntime( 1722): java.lang.InternalError: Thread starting during runtime shutdown
09-03 09:21:32.843 E/AndroidRuntime( 1722): 	at java.lang.Thread.nativeCreate(Native Method)
09-03 09:21:32.843 E/AndroidRuntime( 1722): 	at java.lang.Thread.start(Thread.java:733)
09-03 09:21:32.843 E/AndroidRuntime( 1722): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-03 09:21:32.843 E/AndroidRuntime( 1722): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-03 09:21:32.843 E/AndroidRuntime( 1722): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-03 09:21:32.843 E/AndroidRuntime( 1722): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-03 09:21:32.843 E/AndroidRuntime( 1722): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-03 09:21:32.843 E/AndroidRuntime( 1722): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-03 09:21:32.843 E/AndroidRuntime( 1722): 	at tcs.bca.<init>(SourceFile:24)
09-03 09:21:32.843 E/AndroidRuntime( 1722): 	at tcs.bcb.dv(SourceFile:157)
09-03 09:21:32.843 E/AndroidRuntime( 1722): 	at tcs.bcb.b(SourceFile:135)
09-03 09:21:32.843 E/AndroidRuntime( 1722): 	at tcs.bcb.uF(SourceFile:229)
09-03 09:21:32.843 E/AndroidRuntime( 1722): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-03 09:21:32.843 E/AndroidRuntime( 1722): 	at android.os.Handler.handleCallback(Handler.java:790)
09-03 09:21:32.843 E/AndroidRuntime( 1722): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-03 09:21:32.843 E/AndroidRuntime( 1722): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-03 09:21:32.843 E/AndroidRuntime( 1722): 	at android.os.Looper.loop(Looper.java:164)
09-03 09:21:32.843 E/AndroidRuntime( 1722): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-03 09:21:32.843 E/AndroidRuntime( 1722): 	at tcs.alk.run(SourceFile:79)
09-03 09:21:32.979 E/AndroidRuntime( 1722): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-03 09:21:32.979 E/AndroidRuntime( 1722): Process: com.tencent.qqpimsecure, PID: 1722
09-03 09:21:32.979 E/AndroidRuntime( 1722): java.lang.reflect.UndeclaredThrowableException
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at $Proxy5.getPreferenceService(Unknown Source)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at epmt.j.c(SourceFile:1)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at epmt.c.a(SourceFile:2)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at epmt.g.l(SourceFile:99)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at epmt.g.a(SourceFile:2)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at epmt.g$c.handleMessage(SourceFile:1)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at android.os.Looper.loop(Looper.java:164)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at tcs.alk.run(SourceFile:79)
09-03 09:21:32.979 E/AndroidRuntime( 1722): Caused by: java.lang.reflect.InvocationTargetException
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	... 10 more
09-03 09:21:32.979 E/AndroidRuntime( 1722): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at java.lang.Thread.nativeCreate(Native Method)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at java.lang.Thread.start(Thread.java:733)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at tcs.eiv.aq(SourceFile:111)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at tcs.ahr.<init>(SourceFile:16)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-03 09:21:32.979 E/AndroidRuntime( 1722): 	... 13 more
09-03 09:21:33.019 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-03 09:21:33.020 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #75
09-03 09:21:33.049 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #1400
09-03 09:21:35.613 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-03 09:21:35.614 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #75
09-03 09:21:35.625 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #1400
09-03 09:43:04.472 W/FileUtils( 9090): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 09:43:04.483 W/FileUtils( 9090): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 09:43:04.492 W/FileUtils( 9090): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 09:43:04.494 W/FileUtils( 9090): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 09:43:04.924 W/FileUtils( 9090): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 09:43:04.944 W/FileUtils( 9090): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 09:43:05.018 W/PackageParser( 9090): Failed to parse /storage/emulated/0/tencent/tbs/backup/com.tencent.mm/x5.tbs.org
09-03 09:43:05.018 W/PackageParser( 9090): java.io.FileNotFoundException: AndroidManifest.xml
09-03 09:43:05.018 W/PackageParser( 9090): 	at android.content.res.AssetManager.openXmlAssetNative(Native Method)
09-03 09:43:05.018 W/PackageParser( 9090): 	at android.content.res.AssetManager.openXmlBlockAsset(AssetManager.java:560)
09-03 09:43:05.018 W/PackageParser( 9090): 	at android.content.res.AssetManager.openXmlResourceParser(AssetManager.java:528)
09-03 09:43:05.018 W/PackageParser( 9090): 	at android.content.pm.PackageParser.parseApkLite(PackageParser.java:1773)
09-03 09:43:05.018 W/PackageParser( 9090): 	at android.content.pm.PackageParser.parseMonolithicPackageLite(PackageParser.java:906)
09-03 09:43:05.018 W/PackageParser( 9090): 	at android.content.pm.PackageParser.parseMonolithicPackage(PackageParser.java:1294)
09-03 09:43:05.018 W/PackageParser( 9090): 	at android.content.pm.PackageManager.getPackageArchiveInfo(PackageManager.java:4693)
09-03 09:43:05.018 W/PackageParser( 9090): 	at com.tencent.smtt.utils.a.a(Unknown Source:146)
09-03 09:43:05.018 W/PackageParser( 9090): 	at com.tencent.smtt.utils.a.a(Unknown Source:21)
09-03 09:43:05.018 W/PackageParser( 9090): 	at com.tencent.smtt.sdk.TbsDownloader.a(Unknown Source:65)
09-03 09:43:05.018 W/PackageParser( 9090): 	at com.tencent.smtt.sdk.l.a(Unknown Source:69)
09-03 09:43:05.018 W/PackageParser( 9090): 	at com.tencent.smtt.sdk.TbsDownloader.a(Unknown Source:1731)
09-03 09:43:05.018 W/PackageParser( 9090): 	at com.tencent.smtt.sdk.TbsDownloader.b(Unknown Source:913)
09-03 09:43:05.018 W/PackageParser( 9090): 	at com.tencent.smtt.sdk.TbsDownloader.a(Unknown Source:0)
09-03 09:43:05.018 W/PackageParser( 9090): 	at com.tencent.smtt.sdk.TbsDownloader$2.handleMessage(Unknown Source:164)
09-03 09:43:05.018 W/PackageParser( 9090): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-03 09:43:05.018 W/PackageParser( 9090): 	at android.os.Looper.loop(Looper.java:164)
09-03 09:43:05.018 W/PackageParser( 9090): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-03 09:43:05.244 W/FileUtils( 9090): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 09:43:05.249 W/FileUtils( 9090): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 09:43:05.265 W/FileUtils( 9090): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 09:43:05.267 W/FileUtils( 9090): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 09:43:08.735 E/ActivityThread( 9430): Failed to find provider info for com.vivo.push.sdk.service.SystemPushConfig
09-03 10:07:54.612 W/ViewRootImpl[PopupWindow:b7ca413]( 9090): Dropping event due to root view being removed: MotionEvent { action=ACTION_UP, actionButton=0, id[0]=0, x[0]=259.7595, y[0]=-47.075256, toolType[0]=TOOL_TYPE_FINGER, buttonState=0, metaState=0, flags=0x0, edgeFlags=0x0, pointerCount=1, historySize=0, eventTime=225396518, downTime=225396504, deviceId=5, source=0x1002 }
09-03 10:08:04.740 W/vold    (  228): Failed to read namespace for 9317: No such file or directory
09-03 10:08:04.740 W/vold    (  228): Failed to read namespace for 9318: No such file or directory
09-03 10:08:04.740 W/vold    (  228): Failed to read namespace for 9359: No such file or directory
09-03 10:08:04.740 W/vold    (  228): Failed to read namespace for 9361: No such file or directory
09-03 10:08:04.740 W/vold    (  228): Failed to read namespace for 9378: No such file or directory
09-03 10:08:04.748 W/vold    (  228): Failed to read namespace for 9460: No such file or directory
09-03 10:08:04.770 W/vold    (  228): Failed to read namespace for 9317: No such file or directory
09-03 10:08:04.770 W/vold    (  228): Failed to read namespace for 9318: No such file or directory
09-03 10:08:04.771 W/vold    (  228): Failed to read namespace for 9359: No such file or directory
09-03 10:08:04.771 W/vold    (  228): Failed to read namespace for 9361: No such file or directory
09-03 10:08:04.771 W/vold    (  228): Failed to read namespace for 9378: No such file or directory
09-03 10:08:04.779 W/vold    (  228): Failed to read namespace for 9460: No such file or directory
09-03 10:41:58.052 E/AndroidRuntime(19668): FATAL EXCEPTION: main
09-03 10:41:58.052 E/AndroidRuntime(19668): Process: com.tencent.qqpimsecure, PID: 19668
09-03 10:41:58.052 E/AndroidRuntime(19668): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at android.os.Looper.loop(Looper.java:164)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-03 10:41:58.052 E/AndroidRuntime(19668): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	... 8 more
09-03 10:41:58.052 E/AndroidRuntime(19668): Caused by: java.lang.reflect.UndeclaredThrowableException
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at $Proxy5.init(Unknown Source)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	... 12 more
09-03 10:41:58.052 E/AndroidRuntime(19668): Caused by: java.lang.reflect.InvocationTargetException
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	... 16 more
09-03 10:41:58.052 E/AndroidRuntime(19668): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{40d15ce u0a77 TRNB idle change:uncached procs:1 seq(0,0,0)}
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at epetrp.b.c(SourceFile:8)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	at epetrp.c.init(SourceFile:1)
09-03 10:41:58.052 E/AndroidRuntime(19668): 	... 19 more
09-03 10:42:03.024 E/AndroidRuntime(19668): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-03 10:42:03.024 E/AndroidRuntime(19668): Process: com.tencent.qqpimsecure, PID: 19668
09-03 10:42:03.024 E/AndroidRuntime(19668): java.lang.InternalError: Thread starting during runtime shutdown
09-03 10:42:03.024 E/AndroidRuntime(19668): 	at java.lang.Thread.nativeCreate(Native Method)
09-03 10:42:03.024 E/AndroidRuntime(19668): 	at java.lang.Thread.start(Thread.java:733)
09-03 10:42:03.024 E/AndroidRuntime(19668): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-03 10:42:03.024 E/AndroidRuntime(19668): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-03 10:42:03.024 E/AndroidRuntime(19668): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-03 10:42:03.024 E/AndroidRuntime(19668): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-03 10:42:03.024 E/AndroidRuntime(19668): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-03 10:42:03.024 E/AndroidRuntime(19668): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-03 10:42:03.024 E/AndroidRuntime(19668): 	at tcs.bca.<init>(SourceFile:24)
09-03 10:42:03.024 E/AndroidRuntime(19668): 	at tcs.bcb.dv(SourceFile:157)
09-03 10:42:03.024 E/AndroidRuntime(19668): 	at tcs.bcb.b(SourceFile:135)
09-03 10:42:03.024 E/AndroidRuntime(19668): 	at tcs.bcb.uF(SourceFile:229)
09-03 10:42:03.024 E/AndroidRuntime(19668): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-03 10:42:03.024 E/AndroidRuntime(19668): 	at android.os.Handler.handleCallback(Handler.java:790)
09-03 10:42:03.024 E/AndroidRuntime(19668): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-03 10:42:03.024 E/AndroidRuntime(19668): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-03 10:42:03.024 E/AndroidRuntime(19668): 	at android.os.Looper.loop(Looper.java:164)
09-03 10:42:03.024 E/AndroidRuntime(19668): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-03 10:42:03.024 E/AndroidRuntime(19668): 	at tcs.alk.run(SourceFile:79)
09-03 10:42:03.060 E/AndroidRuntime(19668): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-03 10:42:03.060 E/AndroidRuntime(19668): Process: com.tencent.qqpimsecure, PID: 19668
09-03 10:42:03.060 E/AndroidRuntime(19668): java.lang.reflect.UndeclaredThrowableException
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at $Proxy6.getPreferenceService(Unknown Source)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at epmt.j.c(SourceFile:1)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at epmt.c.a(SourceFile:2)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at epmt.g.l(SourceFile:99)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at epmt.g.a(SourceFile:2)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at epmt.g$c.handleMessage(SourceFile:1)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at android.os.Looper.loop(Looper.java:164)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at tcs.alk.run(SourceFile:79)
09-03 10:42:03.060 E/AndroidRuntime(19668): Caused by: java.lang.reflect.InvocationTargetException
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	... 10 more
09-03 10:42:03.060 E/AndroidRuntime(19668): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at java.lang.Thread.nativeCreate(Native Method)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at java.lang.Thread.start(Thread.java:733)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at tcs.eiv.aq(SourceFile:111)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at tcs.ahr.<init>(SourceFile:16)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-03 10:42:03.060 E/AndroidRuntime(19668): 	... 13 more
09-03 10:43:19.211 W/FileUtils(20282): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 10:43:19.221 W/FileUtils(20282): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 10:43:19.242 W/FileUtils(20282): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 10:43:19.242 W/FileUtils(20282): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 10:43:19.808 W/FileUtils(20282): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 10:43:19.809 W/FileUtils(20282): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 10:43:19.810 W/FileUtils(20282): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 10:43:19.810 W/FileUtils(20282): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 11:25:20.259 E/AndroidRuntime(28374): FATAL EXCEPTION: main
09-03 11:25:20.259 E/AndroidRuntime(28374): Process: com.tencent.qqpimsecure, PID: 28374
09-03 11:25:20.259 E/AndroidRuntime(28374): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at android.os.Looper.loop(Looper.java:164)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-03 11:25:20.259 E/AndroidRuntime(28374): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	... 8 more
09-03 11:25:20.259 E/AndroidRuntime(28374): Caused by: java.lang.reflect.UndeclaredThrowableException
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at $Proxy5.init(Unknown Source)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	... 12 more
09-03 11:25:20.259 E/AndroidRuntime(28374): Caused by: java.lang.reflect.InvocationTargetException
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	... 16 more
09-03 11:25:20.259 E/AndroidRuntime(28374): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{cc575bd u0a77 TRNB idle change:idle|uncached procs:1 seq(0,0,0)}
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at epetrp.b.c(SourceFile:8)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	at epetrp.c.init(SourceFile:1)
09-03 11:25:20.259 E/AndroidRuntime(28374): 	... 19 more
09-03 11:25:25.237 E/AndroidRuntime(28374): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-03 11:25:25.237 E/AndroidRuntime(28374): Process: com.tencent.qqpimsecure, PID: 28374
09-03 11:25:25.237 E/AndroidRuntime(28374): java.lang.InternalError: Thread starting during runtime shutdown
09-03 11:25:25.237 E/AndroidRuntime(28374): 	at java.lang.Thread.nativeCreate(Native Method)
09-03 11:25:25.237 E/AndroidRuntime(28374): 	at java.lang.Thread.start(Thread.java:733)
09-03 11:25:25.237 E/AndroidRuntime(28374): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-03 11:25:25.237 E/AndroidRuntime(28374): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-03 11:25:25.237 E/AndroidRuntime(28374): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-03 11:25:25.237 E/AndroidRuntime(28374): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-03 11:25:25.237 E/AndroidRuntime(28374): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-03 11:25:25.237 E/AndroidRuntime(28374): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-03 11:25:25.237 E/AndroidRuntime(28374): 	at tcs.bca.<init>(SourceFile:24)
09-03 11:25:25.237 E/AndroidRuntime(28374): 	at tcs.bcb.dv(SourceFile:157)
09-03 11:25:25.237 E/AndroidRuntime(28374): 	at tcs.bcb.b(SourceFile:135)
09-03 11:25:25.237 E/AndroidRuntime(28374): 	at tcs.bcb.uF(SourceFile:229)
09-03 11:25:25.237 E/AndroidRuntime(28374): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-03 11:25:25.237 E/AndroidRuntime(28374): 	at android.os.Handler.handleCallback(Handler.java:790)
09-03 11:25:25.237 E/AndroidRuntime(28374): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-03 11:25:25.237 E/AndroidRuntime(28374): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-03 11:25:25.237 E/AndroidRuntime(28374): 	at android.os.Looper.loop(Looper.java:164)
09-03 11:25:25.237 E/AndroidRuntime(28374): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-03 11:25:25.237 E/AndroidRuntime(28374): 	at tcs.alk.run(SourceFile:79)
09-03 11:25:25.263 E/AndroidRuntime(28374): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-03 11:25:25.263 E/AndroidRuntime(28374): Process: com.tencent.qqpimsecure, PID: 28374
09-03 11:25:25.263 E/AndroidRuntime(28374): java.lang.reflect.UndeclaredThrowableException
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at $Proxy6.getPreferenceService(Unknown Source)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at epmt.j.c(SourceFile:1)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at epmt.c.a(SourceFile:2)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at epmt.g.l(SourceFile:99)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at epmt.g.a(SourceFile:2)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at epmt.g$c.handleMessage(SourceFile:1)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at android.os.Looper.loop(Looper.java:164)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at tcs.alk.run(SourceFile:79)
09-03 11:25:25.263 E/AndroidRuntime(28374): Caused by: java.lang.reflect.InvocationTargetException
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	... 10 more
09-03 11:25:25.263 E/AndroidRuntime(28374): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at java.lang.Thread.nativeCreate(Native Method)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at java.lang.Thread.start(Thread.java:733)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at tcs.eiv.aq(SourceFile:111)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at tcs.ahr.<init>(SourceFile:16)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-03 11:25:25.263 E/AndroidRuntime(28374): 	... 13 more
09-03 11:32:06.818 W/FileUtils( 3186): Failed to chmod(/data/user/0/com.tencent.android.qqdownloader/shared_prefs/qmsp_cbid_time.xml): android.system.ErrnoException: chmod failed: ENOENT (No such file or directory)
09-03 11:36:51.856 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 11:37:39.983 W/NotificationService(  620): Toast already cancelled. pkg=com.shinyv.cnr callback=android.app.ITransientNotification$Stub$Proxy@ccf7b65
09-03 11:37:40.819 W/NotificationService(  620): Toast already cancelled. pkg=com.shinyv.cnr callback=android.app.ITransientNotification$Stub$Proxy@6a58af4
09-03 11:37:41.187 W/NotificationService(  620): Toast already cancelled. pkg=com.shinyv.cnr callback=android.app.ITransientNotification$Stub$Proxy@53e9663
09-03 11:37:41.443 W/NotificationService(  620): Toast already cancelled. pkg=com.shinyv.cnr callback=android.app.ITransientNotification$Stub$Proxy@c7a35bf
09-03 11:37:41.687 W/NotificationService(  620): Toast already cancelled. pkg=com.shinyv.cnr callback=android.app.ITransientNotification$Stub$Proxy@7276bea
09-03 11:37:41.862 W/NotificationService(  620): Toast already cancelled. pkg=com.shinyv.cnr callback=android.app.ITransientNotification$Stub$Proxy@a654c51
09-03 11:37:43.855 W/WindowManager(  620): removeWindowToken: Attempted to remove non-existing token: android.os.Binder@2960c5c
09-03 11:37:53.327 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 11:37:56.694 W/NotificationService(  620): Toast already cancelled. pkg=com.shinyv.cnr callback=android.app.ITransientNotification$Stub$Proxy@fe15c8d
09-03 11:37:58.695 W/WindowManager(  620): removeWindowToken: Attempted to remove non-existing token: android.os.Binder@83b9924
09-03 11:38:05.594 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 11:38:53.344 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 11:39:54.826 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 11:40:54.837 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 11:41:56.343 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 11:42:57.873 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 11:43:05.599 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 11:43:59.341 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 11:45:00.820 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 11:46:02.329 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 11:46:43.223 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 11:48:51.492 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 11:54:15.089 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 11:54:15.089 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 11:54:15.115 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 11:54:32.096 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 11:58:49.366 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 12:01:20.996 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 12:01:20.997 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 12:01:21.009 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 12:01:33.090 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 12:01:33.091 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 12:01:33.107 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 12:02:09.096 W/BroadcastQueue(  620): Permission Denial: receiving Intent { act=android.bluetooth.device.action.FOUND flg=0x10 (has extras) } to ProcessRecord{c27c6b3 9430:com.shinyv.cnr:pushservice/u0a1139} (pid=9430, uid=11139) requires android.permission.ACCESS_COARSE_LOCATION due to sender com.android.bluetooth (uid 1002)
09-03 12:02:17.246 W/BroadcastQueue(  620): Permission Denial: receiving Intent { act=android.bluetooth.device.action.FOUND flg=0x10 (has extras) } to ProcessRecord{c27c6b3 9430:com.shinyv.cnr:pushservice/u0a1139} (pid=9430, uid=11139) requires android.permission.ACCESS_COARSE_LOCATION due to sender com.android.bluetooth (uid 1002)
09-03 12:03:11.113 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 12:08:06.403 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 12:08:27.081 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 12:08:27.081 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 12:08:27.098 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 12:12:02.765 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.android.qqdownloader.action.SCHEDULE_JOB flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.module.timer.ScheduleJobReceiver
09-03 12:14:32.088 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 12:15:33.088 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 12:15:33.088 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 12:15:33.109 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 12:19:56.948 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 12:22:09.092 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 12:22:09.093 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 12:22:09.121 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 12:23:05.597 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 12:28:05.596 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 12:29:21.093 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 12:29:21.093 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 12:29:21.116 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 12:31:20.996 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 12:31:20.996 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 12:31:21.012 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 12:34:32.085 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 12:35:49.480 W/BroadcastQueue(  620): Permission Denial: receiving Intent { act=android.bluetooth.device.action.FOUND flg=0x10 (has extras) } to ProcessRecord{c27c6b3 9430:com.shinyv.cnr:pushservice/u0a1139} (pid=9430, uid=11139) requires android.permission.ACCESS_COARSE_LOCATION due to sender com.android.bluetooth (uid 1002)
09-03 12:35:52.771 W/BroadcastQueue(  620): Permission Denial: receiving Intent { act=android.bluetooth.device.action.FOUND flg=0x10 (has extras) } to ProcessRecord{c27c6b3 9430:com.shinyv.cnr:pushservice/u0a1139} (pid=9430, uid=11139) requires android.permission.ACCESS_COARSE_LOCATION due to sender com.android.bluetooth (uid 1002)
09-03 12:35:54.932 W/BroadcastQueue(  620): Permission Denial: receiving Intent { act=android.bluetooth.device.action.FOUND flg=0x10 (has extras) } to ProcessRecord{c27c6b3 9430:com.shinyv.cnr:pushservice/u0a1139} (pid=9430, uid=11139) requires android.permission.ACCESS_COARSE_LOCATION due to sender com.android.bluetooth (uid 1002)
09-03 12:36:21.090 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 12:36:21.090 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 12:36:21.104 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 12:38:18.012 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 12:43:15.094 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 12:43:15.094 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 12:43:15.111 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 12:43:23.548 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 12:48:05.598 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 12:50:33.096 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 12:50:33.096 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 12:50:33.121 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 12:53:05.597 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 12:57:21.098 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 12:57:21.108 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 12:57:21.131 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 12:58:54.308 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 13:00:06.501 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 13:01:21.032 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 13:01:21.032 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 13:01:21.046 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 13:03:05.593 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 13:04:39.094 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 13:04:39.094 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 13:04:39.115 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 13:07:49.614 W/BroadcastQueue(  620): Permission Denial: receiving Intent { act=android.bluetooth.device.action.FOUND flg=0x10 (has extras) } to ProcessRecord{c27c6b3 9430:com.shinyv.cnr:pushservice/u0a1139} (pid=9430, uid=11139) requires android.permission.ACCESS_COARSE_LOCATION due to sender com.android.bluetooth (uid 1002)
09-03 13:07:55.766 W/BroadcastQueue(  620): Permission Denial: receiving Intent { act=android.bluetooth.device.action.FOUND flg=0x10 (has extras) } to ProcessRecord{c27c6b3 9430:com.shinyv.cnr:pushservice/u0a1139} (pid=9430, uid=11139) requires android.permission.ACCESS_COARSE_LOCATION due to sender com.android.bluetooth (uid 1002)
09-03 13:08:05.596 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 13:10:39.111 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 13:10:39.111 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 13:10:39.134 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 13:14:32.089 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 13:15:37.030 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher2.permission.READ_SETTINGS in package: com.tencent.mobileqq at: Binary XML file line #83
09-03 13:15:37.031 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WRITE_CONTACTS in package: com.tencent.mobileqq at: Binary XML file line #114
09-03 13:15:37.121 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #185
09-03 13:15:37.121 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CHANGE_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #192
09-03 13:15:37.121 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.INTERNET in package: com.tencent.mobileqq at: Binary XML file line #193
09-03 13:15:37.121 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #194
09-03 13:15:37.121 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_NETWORK_STATE in package: com.tencent.mobileqq at: Binary XML file line #195
09-03 13:15:37.121 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CAMERA in package: com.tencent.mobileqq at: Binary XML file line #199
09-03 13:15:37.121 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.tencent.mobileqq at: Binary XML file line #200
09-03 13:15:37.121 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WAKE_LOCK in package: com.tencent.mobileqq at: Binary XML file line #201
09-03 13:15:37.121 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher.permission.INSTALL_SHORTCUT in package: com.tencent.mobileqq at: Binary XML file line #202
09-03 13:15:37.121 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.RECEIVE_BOOT_COMPLETED in package: com.tencent.mobileqq at: Binary XML file line #203
09-03 13:15:37.122 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #205
09-03 13:15:37.139 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Android/data/com.tencent.mobileqq/Tencent/TMAssistantSDK/Download/com.tencent.mobileqq/AndroidBBPJQQ_8.8.17.5770_537084958_bbb5f11ab5cf828c12abf84c5b33db55.apk Binary XML file line #2062
09-03 13:15:41.556 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.qqpimsecure-6755.apk Binary XML file line #836
09-03 13:15:41.815 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.sohu.inputmethod.sogou1460.apk Binary XML file line #264
09-03 13:15:41.927 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.qqpimsecure-6790.apk Binary XML file line #834
09-03 13:15:42.020 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher2.permission.READ_SETTINGS in package: com.tencent.mobileqq at: Binary XML file line #81
09-03 13:15:42.021 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WRITE_CONTACTS in package: com.tencent.mobileqq at: Binary XML file line #112
09-03 13:15:42.021 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #183
09-03 13:15:42.022 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CHANGE_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #190
09-03 13:15:42.022 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.INTERNET in package: com.tencent.mobileqq at: Binary XML file line #191
09-03 13:15:42.022 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_WIFI_STATE in package: com.tencent.mobileqq at: Binary XML file line #192
09-03 13:15:42.022 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.ACCESS_NETWORK_STATE in package: com.tencent.mobileqq at: Binary XML file line #193
09-03 13:15:42.022 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.CAMERA in package: com.tencent.mobileqq at: Binary XML file line #197
09-03 13:15:42.022 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.tencent.mobileqq at: Binary XML file line #198
09-03 13:15:42.022 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.WAKE_LOCK in package: com.tencent.mobileqq at: Binary XML file line #199
09-03 13:15:42.022 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.android.launcher.permission.INSTALL_SHORTCUT in package: com.tencent.mobileqq at: Binary XML file line #200
09-03 13:15:42.022 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.RECEIVE_BOOT_COMPLETED in package: com.tencent.mobileqq at: Binary XML file line #201
09-03 13:15:42.022 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: com.tencent.msf.permission.account.sync in package: com.tencent.mobileqq at: Binary XML file line #203
09-03 13:15:42.034 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/QQSecureDownload/com.tencent.mobileqq1792.apk Binary XML file line #2077
09-03 13:15:42.605 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-03 13:15:42.606 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/Download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #75
09-03 13:15:42.618 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/Download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #1400
09-03 13:15:44.963 W/PackageParser( 3663): Ignoring duplicate uses-permissions/uses-permissions-sdk-m: android.permission.READ_PHONE_STATE in package: com.shinyv.cnr at: Binary XML file line #26
09-03 13:15:44.964 W/PackageParser( 3663): Unknown element under <manifest>: meta-data at /storage/emulated/0/download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #75
09-03 13:15:44.974 W/PackageParser( 3663): No actions in intent filter at /storage/emulated/0/download/WeiXin/yt_v6.34.0.8738.apk Binary XML file line #1400
09-03 13:16:27.110 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 13:16:27.110 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 13:16:27.143 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 13:20:00.975 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 13:22:03.090 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 13:22:03.091 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 13:22:03.106 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 13:24:32.114 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 13:27:51.103 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 13:27:51.103 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 13:27:51.128 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 13:28:18.270 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 13:31:21.056 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 13:31:21.056 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 13:31:21.070 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 13:33:10.965 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 13:33:27.095 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 13:33:27.095 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 13:33:27.113 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 13:38:05.596 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 13:38:57.084 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 13:38:57.084 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 13:38:57.107 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 13:39:50.093 W/BroadcastQueue(  620): Permission Denial: receiving Intent { act=android.bluetooth.device.action.FOUND flg=0x10 (has extras) } to ProcessRecord{c27c6b3 9430:com.shinyv.cnr:pushservice/u0a1139} (pid=9430, uid=11139) requires android.permission.ACCESS_COARSE_LOCATION due to sender com.android.bluetooth (uid 1002)
09-03 13:39:58.429 W/BroadcastQueue(  620): Permission Denial: receiving Intent { act=android.bluetooth.device.action.FOUND flg=0x10 (has extras) } to ProcessRecord{c27c6b3 9430:com.shinyv.cnr:pushservice/u0a1139} (pid=9430, uid=11139) requires android.permission.ACCESS_COARSE_LOCATION due to sender com.android.bluetooth (uid 1002)
09-03 13:43:05.604 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 13:43:21.355 W/BackupTransportManager(  620): Transport com.google.android.gms/.backup.BackupTransportService not bound.
09-03 13:45:09.091 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 13:45:09.091 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 13:45:09.120 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 13:48:19.011 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 13:51:45.090 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 13:51:45.090 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 13:51:45.114 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 13:54:32.166 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 13:56:58.263 W/ActivityManager(  620): Background start not allowed: service Intent { cmp=com.tencent.mobileqq/.msf.service.MsfService (has extras) } to com.tencent.mobileqq/.msf.service.MsfService from pid=15741 uid=10986 pkg=com.tencent.mobileqq
09-03 13:58:15.098 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 13:58:15.098 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 13:58:15.129 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 13:59:53.406 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 14:01:21.098 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 14:01:21.098 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 14:01:21.113 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 14:03:35.355 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=android.intent.action.ACTION_POWER_DISCONNECTED flg=0x4000010 (has extras) } to com.tencent.android.qqdownloader/com.qq.AppService.MainReceiver
09-03 14:03:35.355 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=android.intent.action.ACTION_POWER_DISCONNECTED flg=0x4000010 (has extras) } to com.shinyv.cnr/com.igexin.sdk.PushReceiver
09-03 14:03:35.355 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=android.intent.action.ACTION_POWER_DISCONNECTED flg=0x4000010 (has extras) } to io.appium.uiautomator2.server/.ServerInstrumentation$PowerConnectionReceiver
09-03 14:03:35.393 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 14:03:35.395 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 14:03:35.423 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 14:03:35.537 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 14:03:35.644 W/PowerManagerService(  620): Screen on took 295 ms
09-03 14:03:36.439 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 14:03:38.797 W/ActivityManager(  620): Expected user 0 in state RUNNING_LOCKED but was in state RUNNING_UNLOCKED
09-03 14:03:39.248 W/BroadcastQueue(  620): Permission Denial: broadcasting Intent { act=android.intent.action.USER_PRESENT flg=0x24200010 } from com.android.systemui (pid=2100, uid=10027) is not exported from uid 10077 due to receiver com.tencent.qqpimsecure/com.tencent.server.back.FastBootReceiver
09-03 14:03:39.253 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=android.intent.action.USER_PRESENT flg=0x24200010 } to com.shinyv.cnr/com.igexin.sdk.PushReceiver
09-03 14:03:39.254 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=android.intent.action.USER_PRESENT flg=0x24200010 } to com.taobao.taobao/com.taobao.accs.EventReceiver
09-03 14:03:39.254 W/BroadcastQueue(  620): Permission Denial: broadcasting Intent { act=android.intent.action.USER_PRESENT flg=0x24200010 } from com.android.systemui (pid=2100, uid=10027) is not exported from uid 10934 due to receiver com.tencent.android.qqdownloader/com.tencent.assistant.module.timer.ScheduleJobReceiver
09-03 14:03:40.490 W/ActivityManager(  620): Unable to start service Intent { cmp=sogou.mobile.explorer/.ActivateBrowserService } U=0: not found
09-03 14:03:40.601 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 14:03:55.408 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 14:03:55.987 W/ActivityManager(  620): Unable to start service Intent { act=com.android.launcher3.WINDOW_OVERLAY dat=app://org.lineageos.trebuchet:10029?v=7&cv=9 pkg=com.google.android.googlequicksearchbox } U=0: not found
09-03 14:04:15.135 W/ActivityManager(  620): Launch timeout has expired, giving up wake lock!
09-03 14:04:40.612 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 14:05:42.105 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 14:05:51.112 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 14:05:51.112 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 14:05:51.131 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 14:06:25.070 W/ActivityManager(  620): Launch timeout has expired, giving up wake lock!
09-03 14:06:43.606 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 14:07:01.433 W/ActivityManager(  620): Duplicate finish request for ActivityRecord{4cc96fd u0 com.shinyv.cnr/com.linker.xlyt.read.ui.activity.joker.recommend.UploadMyVoiceActivity t29261 f}
09-03 14:07:01.466 W/NotificationService(  620): Toast already cancelled. pkg=com.shinyv.cnr callback=android.app.ITransientNotification$Stub$Proxy@afdccc6
09-03 14:07:03.467 W/WindowManager(  620): removeWindowToken: Attempted to remove non-existing token: android.os.Binder@10b6b08
09-03 14:07:11.398 W/NotificationService(  620): Toast already cancelled. pkg=com.shinyv.cnr callback=android.app.ITransientNotification$Stub$Proxy@3fcd7c5
09-03 14:07:13.379 W/WindowManager(  620): removeWindowToken: Attempted to remove non-existing token: android.os.Binder@6afa60e
09-03 14:07:15.122 W/NotificationService(  620): Toast already cancelled. pkg=com.shinyv.cnr callback=android.app.ITransientNotification$Stub$Proxy@eed3ae9
09-03 14:07:17.093 W/WindowManager(  620): removeWindowToken: Attempted to remove non-existing token: android.os.Binder@512d722
09-03 14:07:45.097 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 14:07:45.097 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 14:07:45.113 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 14:07:45.120 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 14:08:29.821 E/AndroidRuntime( 9090): FATAL EXCEPTION: main
09-03 14:08:29.821 E/AndroidRuntime( 9090): Process: com.shinyv.cnr, PID: 9090
09-03 14:08:29.821 E/AndroidRuntime( 9090): java.lang.IndexOutOfBoundsException: Index: 0, Size: 0
09-03 14:08:29.821 E/AndroidRuntime( 9090): 	at java.util.ArrayList.get(ArrayList.java:437)
09-03 14:08:29.821 E/AndroidRuntime( 9090): 	at com.linker.xlyt.read.ui.activity.home.TextListActivity.lambda$initRecyclerview$2$TextListActivity(TextListActivity.java:229)
09-03 14:08:29.821 E/AndroidRuntime( 9090): 	at com.linker.xlyt.read.ui.activity.home.-$$Lambda$TextListActivity$2UA017t2jG3kgj-IbnPJeQqA1gw.onClick(Unknown Source:2)
09-03 14:08:29.821 E/AndroidRuntime( 9090): 	at com.linker.xlyt.read.adapter.TextListAdapter.lambda$convert$0$TextListAdapter(TextListAdapter.java:33)
09-03 14:08:29.821 E/AndroidRuntime( 9090): 	at com.linker.xlyt.read.adapter.-$$Lambda$TextListAdapter$liDoPlF7g2fnwekxWvbtwpKwLp0.onItemClick(Unknown Source:4)
09-03 14:08:29.821 E/AndroidRuntime( 9090): 	at com.chad.library.adapter.base.BaseQuickAdapter$5.onClick(BaseQuickAdapter.java:956)
09-03 14:08:29.821 E/AndroidRuntime( 9090): 	at android.view.View.performClick(View.java:6294)
09-03 14:08:29.821 E/AndroidRuntime( 9090): 	at android.view.View$PerformClick.run(View.java:24770)
09-03 14:08:29.821 E/AndroidRuntime( 9090): 	at android.os.Handler.handleCallback(Handler.java:790)
09-03 14:08:29.821 E/AndroidRuntime( 9090): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-03 14:08:29.821 E/AndroidRuntime( 9090): 	at android.os.Looper.loop(Looper.java:164)
09-03 14:08:29.821 E/AndroidRuntime( 9090): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-03 14:08:29.821 E/AndroidRuntime( 9090): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 14:08:29.821 E/AndroidRuntime( 9090): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-03 14:08:29.821 E/AndroidRuntime( 9090): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-03 14:08:29.858 W/ActivityManager(  620):   Force finishing activity com.shinyv.cnr/com.linker.xlyt.read.ui.activity.home.TextListActivity
09-03 14:08:30.360 W/ActivityManager(  620): Activity pause timeout for ActivityRecord{54b126 u0 com.shinyv.cnr/com.linker.xlyt.read.ui.activity.home.TextListActivity t29261 f}
09-03 14:08:31.532 W/ActivityManager(  620): Scheduling restart of crashed service com.shinyv.cnr/com.linker.xlyt.components.service.XlPlayerService in 1000ms
09-03 14:08:31.533 W/ActivityManager(  620): Scheduling restart of crashed service com.shinyv.cnr/com.linker.xlyt.components.service.PlayerService in 11000ms
09-03 14:08:31.578 E/ActivityManager(  620): applyOptionsLocked: Unknown animationType=0
09-03 14:08:31.737 W/ActivityManager(  620): setHasOverlayUi called on unknown pid: 9090
09-03 14:08:31.745 W/ActivityManager(  620): Scheduling restart of crashed service com.shinyv.cnr/com.netease.nimlib.service.NimService in 1000ms
09-03 14:08:31.748 W/ActivityManager(  620): Unable to start service Intent { act=com.android.launcher3.WINDOW_OVERLAY dat=app://org.lineageos.trebuchet:10029?v=7&cv=9 pkg=com.google.android.googlequicksearchbox } U=0: not found
09-03 14:08:31.769 W/AppOps  (  620): Finishing op nesting under-run: uid 1000 pkg android code 24 time=0 duration=0 nesting=0
09-03 14:08:32.127 W/FileUtils(17822): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:08:32.132 W/FileUtils(17822): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:08:32.137 W/FileUtils(17822): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:08:32.139 W/FileUtils(17822): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:08:32.225 W/ActivityManager(  620): Activity pause timeout for ActivityRecord{e3a382e u0 com.shinyv.cnr/com.linker.xlyt.module.homepage.MainActivitys t29261}
09-03 14:08:32.234 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 14:08:32.465 W/FileUtils(17822): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:08:32.466 W/FileUtils(17822): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:08:32.468 W/FileUtils(17822): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:08:32.469 W/FileUtils(17822): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:08:42.039 W/FileUtils(17822): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:08:42.041 W/FileUtils(17822): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:08:42.118 W/FileUtils(17822): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:08:42.119 W/FileUtils(17822): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:08:43.105 W/ActivityManager(  620): Unable to start service Intent { act=action.com.heytap.openid.OPEN_ID_SERVICE cmp=com.heytap.openid/.IdentifyService } U=0: not found
09-03 14:08:43.106 W/ActivityManager(  620): Unable to start service Intent { act=action.com.heytap.openid.OPEN_ID_SERVICE cmp=com.heytap.openid/.IdentifyService } U=0: not found
09-03 14:08:45.154 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 14:09:03.114 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 14:09:03.114 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 14:09:03.133 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 14:09:11.806 W/ViewRootImpl[PopupWindow:aba504](17822): Dropping event due to root view being removed: MotionEvent { action=ACTION_MOVE, actionButton=0, id[0]=0, x[0]=817.2433, y[0]=-43.089783, toolType[0]=TOOL_TYPE_FINGER, buttonState=0, metaState=0, flags=0x0, edgeFlags=0x0, pointerCount=1, historySize=0, eventTime=239873717, downTime=239873690, deviceId=5, source=0x1002 }
09-03 14:09:15.196 E/AndroidRuntime(17822): FATAL EXCEPTION: main
09-03 14:09:15.196 E/AndroidRuntime(17822): Process: com.shinyv.cnr, PID: 17822
09-03 14:09:15.196 E/AndroidRuntime(17822): java.lang.IndexOutOfBoundsException: Inconsistency detected. Invalid item position 2(offset:2).state:8 androidx.recyclerview.widget.RecyclerView{55054e VFED..... ........ 0,0-1080,1578 #7f0907f4 app:id/recycler}, adapter:com.linker.xlyt.read.adapter.TextListAdapter@94f6e23, layout:androidx.recyclerview.widget.LinearLayoutManager@c72bf20, context:com.linker.xlyt.read.ui.activity.home.TextListActivity@e614a92
09-03 14:09:15.196 E/AndroidRuntime(17822): 	at androidx.recyclerview.widget.RecyclerView$Recycler.tryGetViewHolderForPositionByDeadline(RecyclerView.java:6183)
09-03 14:09:15.196 E/AndroidRuntime(17822): 	at androidx.recyclerview.widget.GapWorker.prefetchPositionWithDeadline(GapWorker.java:288)
09-03 14:09:15.196 E/AndroidRuntime(17822): 	at androidx.recyclerview.widget.GapWorker.flushTaskWithDeadline(GapWorker.java:345)
09-03 14:09:15.196 E/AndroidRuntime(17822): 	at androidx.recyclerview.widget.GapWorker.flushTasksWithDeadline(GapWorker.java:361)
09-03 14:09:15.196 E/AndroidRuntime(17822): 	at androidx.recyclerview.widget.GapWorker.prefetch(GapWorker.java:368)
09-03 14:09:15.196 E/AndroidRuntime(17822): 	at androidx.recyclerview.widget.GapWorker.run(GapWorker.java:399)
09-03 14:09:15.196 E/AndroidRuntime(17822): 	at android.os.Handler.handleCallback(Handler.java:790)
09-03 14:09:15.196 E/AndroidRuntime(17822): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-03 14:09:15.196 E/AndroidRuntime(17822): 	at android.os.Looper.loop(Looper.java:164)
09-03 14:09:15.196 E/AndroidRuntime(17822): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-03 14:09:15.196 E/AndroidRuntime(17822): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 14:09:15.196 E/AndroidRuntime(17822): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-03 14:09:15.196 E/AndroidRuntime(17822): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-03 14:09:15.367 W/ActivityManager(  620): Scheduling restart of crashed service com.shinyv.cnr/com.linker.xlyt.components.service.XlPlayerService in 4000ms
09-03 14:09:15.369 W/ActivityManager(  620): Scheduling restart of crashed service com.shinyv.cnr/com.linker.xlyt.components.service.PlayerService in 44000ms
09-03 14:09:15.370 W/ActivityManager(  620): Force removing ActivityRecord{7e9f55f u0 com.shinyv.cnr/com.linker.xlyt.read.ui.activity.home.TextListActivity t29261}: app died, no saved state
09-03 14:09:15.404 W/ActivityManager(  620): setHasOverlayUi called on unknown pid: 17822
09-03 14:09:15.414 W/ActivityManager(  620): Unable to start service Intent { act=com.android.launcher3.WINDOW_OVERLAY dat=app://org.lineageos.trebuchet:10029?v=7&cv=9 pkg=com.google.android.googlequicksearchbox } U=0: not found
09-03 14:09:15.443 W/ActivityManager(  620): Scheduling restart of crashed service com.shinyv.cnr/com.netease.nimlib.service.NimService in 13924ms
09-03 14:09:17.923 W/FileUtils(18426): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:09:17.925 W/FileUtils(18426): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:09:17.945 W/FileUtils(18426): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:09:17.946 W/FileUtils(18426): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:09:19.037 W/ActivityManager(  620): Unable to start service Intent { act=action.com.heytap.openid.OPEN_ID_SERVICE cmp=com.heytap.openid/.IdentifyService } U=0: not found
09-03 14:09:19.037 W/ActivityManager(  620): Unable to start service Intent { act=action.com.heytap.openid.OPEN_ID_SERVICE cmp=com.heytap.openid/.IdentifyService } U=0: not found
09-03 14:09:32.097 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 14:09:32.615 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 14:09:37.165 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.android.qqdownloader.action.SCHEDULE_JOB flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.module.timer.ScheduleJobReceiver
09-03 14:09:46.643 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 14:09:49.221 E/AndroidRuntime(18426): FATAL EXCEPTION: main
09-03 14:09:49.221 E/AndroidRuntime(18426): Process: com.shinyv.cnr, PID: 18426
09-03 14:09:49.221 E/AndroidRuntime(18426): java.lang.IndexOutOfBoundsException: Inconsistency detected. Invalid item position 3(offset:3).state:7 androidx.recyclerview.widget.RecyclerView{e58844a VFED..... .F...... 0,0-1080,1578 #7f0907f4 app:id/recycler}, adapter:com.linker.xlyt.read.adapter.TextListAdapter@474e611, layout:androidx.recyclerview.widget.LinearLayoutManager@6055376, context:com.linker.xlyt.read.ui.activity.home.TextListActivity@95e9db8
09-03 14:09:49.221 E/AndroidRuntime(18426): 	at androidx.recyclerview.widget.RecyclerView$Recycler.tryGetViewHolderForPositionByDeadline(RecyclerView.java:6183)
09-03 14:09:49.221 E/AndroidRuntime(18426): 	at androidx.recyclerview.widget.GapWorker.prefetchPositionWithDeadline(GapWorker.java:288)
09-03 14:09:49.221 E/AndroidRuntime(18426): 	at androidx.recyclerview.widget.GapWorker.flushTaskWithDeadline(GapWorker.java:345)
09-03 14:09:49.221 E/AndroidRuntime(18426): 	at androidx.recyclerview.widget.GapWorker.flushTasksWithDeadline(GapWorker.java:361)
09-03 14:09:49.221 E/AndroidRuntime(18426): 	at androidx.recyclerview.widget.GapWorker.prefetch(GapWorker.java:368)
09-03 14:09:49.221 E/AndroidRuntime(18426): 	at androidx.recyclerview.widget.GapWorker.run(GapWorker.java:399)
09-03 14:09:49.221 E/AndroidRuntime(18426): 	at android.os.Handler.handleCallback(Handler.java:790)
09-03 14:09:49.221 E/AndroidRuntime(18426): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-03 14:09:49.221 E/AndroidRuntime(18426): 	at android.os.Looper.loop(Looper.java:164)
09-03 14:09:49.221 E/AndroidRuntime(18426): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-03 14:09:49.221 E/AndroidRuntime(18426): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 14:09:49.221 E/AndroidRuntime(18426): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-03 14:09:49.221 E/AndroidRuntime(18426): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-03 14:09:49.407 W/ActivityManager(  620): Scheduling restart of crashed service com.shinyv.cnr/com.linker.xlyt.components.service.XlPlayerService in 16000ms
09-03 14:09:49.408 W/ActivityManager(  620): Scheduling restart of crashed service com.shinyv.cnr/com.linker.xlyt.components.service.PushIntentService in 1000ms
09-03 14:09:49.408 W/ActivityManager(  620): Scheduling restart of crashed service com.shinyv.cnr/com.linker.xlyt.components.service.PlayerService in 176000ms
09-03 14:09:49.413 W/ActivityManager(  620): Force removing ActivityRecord{93439ae u0 com.shinyv.cnr/com.linker.xlyt.read.ui.activity.home.TextListActivity t29263}: app died, no saved state
09-03 14:09:49.443 W/ActivityManager(  620): Unable to start service Intent { act=com.android.launcher3.WINDOW_OVERLAY dat=app://org.lineageos.trebuchet:10029?v=7&cv=9 pkg=com.google.android.googlequicksearchbox } U=0: not found
09-03 14:09:49.444 W/ActivityManager(  620): setHasOverlayUi called on unknown pid: 18426
09-03 14:09:49.518 W/ActivityManager(  620): Scheduling restart of crashed service com.shinyv.cnr/com.netease.nimlib.service.NimService in 1000ms
09-03 14:10:05.518 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 14:10:06.523 W/FileUtils(18943): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:10:06.524 W/FileUtils(18943): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:10:06.529 W/FileUtils(18943): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:10:06.529 W/FileUtils(18943): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:10:07.638 W/ActivityManager(  620): Unable to start service Intent { act=action.com.heytap.openid.OPEN_ID_SERVICE cmp=com.heytap.openid/.IdentifyService } U=0: not found
09-03 14:10:07.639 W/ActivityManager(  620): Unable to start service Intent { act=action.com.heytap.openid.OPEN_ID_SERVICE cmp=com.heytap.openid/.IdentifyService } U=0: not found
09-03 14:10:48.146 E/NotificationService(  620): Suppressing notification from package by user request.
--------- beginning of main
09-03 14:10:49.598 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:10:51.102 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:10:51.102 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:10:52.613 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:10:52.613 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:10:54.102 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:10:54.102 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:10:55.597 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:10:55.597 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:10:57.119 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:10:57.120 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:10:58.590 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:10:58.590 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:00.095 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:00.095 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:01.597 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:01.597 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:03.108 E/WifiHAL (  284): wifi_get_logger_supported_feature_set: Error -3 happened. 
09-03 14:11:03.109 E/WifiVendorHal(  620): getSupportedFeatureSet(l.891) failed {.code = ERROR_NOT_SUPPORTED, .description = }
09-03 14:11:03.112 E/WifiHAL (  284): wifi_get_logger_supported_feature_set: Error -3 happened. 
09-03 14:11:03.149 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 14:11:03.149 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 14:11:03.189 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 14:11:03.198 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:03.199 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:04.599 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:04.600 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:06.099 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:06.100 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:07.590 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:07.590 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:09.129 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:09.129 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:10.618 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:10.619 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:12.132 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:12.132 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:13.638 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:13.638 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:15.132 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:15.132 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:16.629 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:16.629 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:18.119 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:18.120 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:19.629 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:19.629 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:21.143 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:21.145 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:22.614 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:22.614 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:24.132 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:24.132 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:25.622 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:25.623 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:27.146 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:27.147 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:28.618 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:28.618 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:30.121 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:30.121 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:31.593 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:31.594 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:33.133 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:33.133 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:34.593 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:34.593 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:36.100 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:36.101 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:36.873 E/AndroidRuntime(18943): FATAL EXCEPTION: main
09-03 14:11:36.873 E/AndroidRuntime(18943): Process: com.shinyv.cnr, PID: 18943
09-03 14:11:36.873 E/AndroidRuntime(18943): java.lang.IndexOutOfBoundsException: Inconsistency detected. Invalid item position 2(offset:2).state:8 androidx.recyclerview.widget.RecyclerView{4eb3f62 VFED..... ........ 0,0-1080,1578 #7f0907f4 app:id/recycler}, adapter:com.linker.xlyt.read.adapter.TextListAdapter@9daae09, layout:androidx.recyclerview.widget.LinearLayoutManager@719080e, context:com.linker.xlyt.read.ui.activity.home.TextListActivity@517e690
09-03 14:11:36.873 E/AndroidRuntime(18943): 	at androidx.recyclerview.widget.RecyclerView$Recycler.tryGetViewHolderForPositionByDeadline(RecyclerView.java:6183)
09-03 14:11:36.873 E/AndroidRuntime(18943): 	at androidx.recyclerview.widget.GapWorker.prefetchPositionWithDeadline(GapWorker.java:288)
09-03 14:11:36.873 E/AndroidRuntime(18943): 	at androidx.recyclerview.widget.GapWorker.flushTaskWithDeadline(GapWorker.java:345)
09-03 14:11:36.873 E/AndroidRuntime(18943): 	at androidx.recyclerview.widget.GapWorker.flushTasksWithDeadline(GapWorker.java:361)
09-03 14:11:36.873 E/AndroidRuntime(18943): 	at androidx.recyclerview.widget.GapWorker.prefetch(GapWorker.java:368)
09-03 14:11:36.873 E/AndroidRuntime(18943): 	at androidx.recyclerview.widget.GapWorker.run(GapWorker.java:399)
09-03 14:11:36.873 E/AndroidRuntime(18943): 	at android.os.Handler.handleCallback(Handler.java:790)
09-03 14:11:36.873 E/AndroidRuntime(18943): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-03 14:11:36.873 E/AndroidRuntime(18943): 	at android.os.Looper.loop(Looper.java:164)
09-03 14:11:36.873 E/AndroidRuntime(18943): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-03 14:11:36.873 E/AndroidRuntime(18943): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 14:11:36.873 E/AndroidRuntime(18943): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-03 14:11:36.873 E/AndroidRuntime(18943): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-03 14:11:37.046 W/zygote  (  620): kill(-18943, 9) failed: No such process
09-03 14:11:37.048 E/Avrcp   ( 2084): play status change 0???0 mPlayStatusChangedNT: 1
09-03 14:11:37.049 W/ActivityManager(  620): Scheduling restart of crashed service com.shinyv.cnr/com.linker.xlyt.components.service.XlPlayerService in 1000ms
09-03 14:11:37.049 W/ActivityManager(  620): Scheduling restart of crashed service com.shinyv.cnr/com.linker.xlyt.components.service.PlayerService in 11000ms
09-03 14:11:37.050 E/Avrcp   ( 2084): play status change 0???0 mPlayStatusChangedNT: 1
09-03 14:11:37.052 W/ActivityManager(  620): Force removing ActivityRecord{ee63bc2 u0 com.shinyv.cnr/com.linker.xlyt.read.ui.activity.home.TextListActivity t29264}: app died, no saved state
09-03 14:11:37.078 W/ActivityManager(  620): setHasOverlayUi called on unknown pid: 18943
09-03 14:11:37.088 W/ActivityManager(  620): Unable to start service Intent { act=com.android.launcher3.WINDOW_OVERLAY dat=app://org.lineageos.trebuchet:10029?v=7&cv=9 pkg=com.google.android.googlequicksearchbox } U=0: not found
09-03 14:11:37.090 W/zygote  (  620): kill(-18943, 9) failed: No such process
09-03 14:11:37.120 W/Adreno-EGL( 3141): <qeglDrvAPI_eglGetConfigAttrib:607>: EGL_BAD_ATTRIBUTE
09-03 14:11:37.133 W/ActivityManager(  620): Scheduling restart of crashed service com.shinyv.cnr/com.netease.nimlib.service.NimService in 20916ms
09-03 14:11:37.134 W/zygote  (  620): kill(-18974, 9) failed: No such process
09-03 14:11:37.607 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:37.607 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:37.662 W/OpenGLRenderer( 3141): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
09-03 14:11:37.662 W/OpenGLRenderer( 3141): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
09-03 14:11:38.200 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 14:11:39.107 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:39.107 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:39.410 W/FileUtils(19529): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:11:39.411 W/FileUtils(19529): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:11:39.456 W/FileUtils(19529): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:11:39.457 W/FileUtils(19529): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:11:39.503 W/System.err(19529): android.content.pm.PackageManager$NameNotFoundException: com.heytap.openid
09-03 14:11:39.503 W/System.err(19529): 	at android.app.ApplicationPackageManager.getPackageInfoAsUser(ApplicationPackageManager.java:173)
09-03 14:11:39.503 W/System.err(19529): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:144)
09-03 14:11:39.503 W/System.err(19529): 	at com.tencent.tbsqmsp.sdk.g.g.e.a(Unknown Source:8)
09-03 14:11:39.503 W/System.err(19529): 	at com.tencent.tbsqmsp.sdk.g.g.b.c(Unknown Source:6)
09-03 14:11:39.503 W/System.err(19529): 	at com.tencent.tbsqmsp.sdk.g.g.c.a(Unknown Source:4)
09-03 14:11:39.503 W/System.err(19529): 	at com.tencent.tbsqmsp.sdk.base.e.a(Unknown Source:117)
09-03 14:11:39.503 W/System.err(19529): 	at com.tencent.tbsqmsp.sdk.u.U.getOAID(Unknown Source:5)
09-03 14:11:39.503 W/System.err(19529): 	at com.tencent.tbsbeacon.a.c.f.O(TbsJavaCore:3)
09-03 14:11:39.503 W/System.err(19529): 	at com.tencent.tbsbeacon.a.c.f.<init>(TbsJavaCore:16)
09-03 14:11:39.503 W/System.err(19529): 	at com.tencent.tbsbeacon.a.c.f.<clinit>(TbsJavaCore:1)
09-03 14:11:39.503 W/System.err(19529): 	at com.tencent.tbsbeacon.a.c.f.p(Unknown Source:0)
09-03 14:11:39.503 W/System.err(19529): 	at com.tencent.tbsbeacon.a.e.b.a(TbsJavaCore:59)
09-03 14:11:39.503 W/System.err(19529): 	at com.tencent.tbsbeacon.e.g.a(TbsJavaCore:11)
09-03 14:11:39.503 W/System.err(19529): 	at com.tencent.tbsbeacon.e.e.run(TbsJavaCore:2)
09-03 14:11:39.503 W/System.err(19529): 	at com.tencent.tbsbeacon.a.b.e.run(TbsJavaCore:1)
09-03 14:11:39.503 W/System.err(19529): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:457)
09-03 14:11:39.503 W/System.err(19529): 	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
09-03 14:11:39.503 W/System.err(19529): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:301)
09-03 14:11:39.503 W/System.err(19529): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1162)
09-03 14:11:39.503 W/System.err(19529): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:636)
09-03 14:11:39.503 W/System.err(19529): 	at java.lang.Thread.run(Thread.java:764)
09-03 14:11:39.583 W/Adreno-EGL(19529): <qeglDrvAPI_eglGetConfigAttrib:607>: EGL_BAD_ATTRIBUTE
09-03 14:11:39.619 W/beacon-thread-1(19682): type=1400 audit(0.0:13384): avc: denied { read } for name="address" dev="sysfs" ino=23017 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:sysfs:s0 tclass=file permissive=0
09-03 14:11:39.658 E/libc    (19529): Access denied finding property "net.dns1"
09-03 14:11:39.660 E/TBSEcService(19529): Emergency configuration has been dispatched, status: 1. Command query: 2000 ignored
09-03 14:11:39.662 W/beacon-thread-1(19682): type=1400 audit(0.0:13385): avc: denied { read } for name="type" dev="sysfs" ino=18777 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:sysfs:s0 tclass=file permissive=0
09-03 14:11:39.662 W/beacon-thread-1(19682): type=1400 audit(0.0:13386): avc: denied { read } for name="name" dev="sysfs" ino=18770 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:sysfs:s0 tclass=file permissive=0
09-03 14:11:39.662 W/beacon-thread-1(19682): type=1400 audit(0.0:13387): avc: denied { read } for name="cid" dev="sysfs" ino=18762 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:sysfs:s0 tclass=file permissive=0
09-03 14:11:39.665 E/DatabaseUtils(  620): Writing exception to parcel
09-03 14:11:39.665 E/DatabaseUtils(  620): java.lang.SecurityException: com.shinyv.cnr was not granted  this permission: android.permission.WRITE_SETTINGS.
09-03 14:11:39.665 E/DatabaseUtils(  620): 	at android.provider.Settings.isCallingPackageAllowedToPerformAppOpsProtectedOperation(Settings.java:11325)
09-03 14:11:39.665 E/DatabaseUtils(  620): 	at android.provider.Settings.checkAndNoteWriteSettingsOperation(Settings.java:11207)
09-03 14:11:39.665 E/DatabaseUtils(  620): 	at com.android.providers.settings.SettingsProvider.mutateSystemSetting(SettingsProvider.java:1380)
09-03 14:11:39.665 E/DatabaseUtils(  620): 	at com.android.providers.settings.SettingsProvider.insertSystemSetting(SettingsProvider.java:1355)
09-03 14:11:39.665 E/DatabaseUtils(  620): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:373)
09-03 14:11:39.665 E/DatabaseUtils(  620): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:401)
09-03 14:11:39.665 E/DatabaseUtils(  620): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:272)
09-03 14:11:39.665 E/DatabaseUtils(  620): 	at android.os.Binder.execTransact(Binder.java:697)
09-03 14:11:40.124 E/libc    (19529): Access denied finding property "net.dns1"
09-03 14:11:40.127 E/libc    (19529): Access denied finding property "net.dns1"
09-03 14:11:40.132 E/libc    (19529): Access denied finding property "net.dns1"
09-03 14:11:40.315 W/System.err(19529): java.io.FileNotFoundException: /data/user/0/com.shinyv.cnr/cache/optlist.ser (No such file or directory)
09-03 14:11:40.316 W/System.err(19529): 	at java.io.FileInputStream.open0(Native Method)
09-03 14:11:40.316 W/System.err(19529): 	at java.io.FileInputStream.open(FileInputStream.java:200)
09-03 14:11:40.316 W/System.err(19529): 	at java.io.FileInputStream.<init>(FileInputStream.java:150)
09-03 14:11:40.316 W/System.err(19529): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
09-03 14:11:40.316 W/System.err(19529): 	at com.tencent.smtt.net.b.a(TbsJavaCore:60)
09-03 14:11:40.316 W/System.err(19529): 	at com.tencent.smtt.net.b.c(TbsJavaCore:170)
09-03 14:11:40.316 W/System.err(19529): 	at com.tencent.smtt.net.NetworkSmttService.preconnectMainResources(TbsJavaCore:151)
09-03 14:11:40.322 E/libc    (19529): Access denied finding property "net.dns1"
09-03 14:11:40.511 W/ActivityManager(  620): Unable to start service Intent { act=action.com.heytap.openid.OPEN_ID_SERVICE cmp=com.heytap.openid/.IdentifyService } U=0: not found
09-03 14:11:40.512 W/ActivityManager(  620): Unable to start service Intent { act=action.com.heytap.openid.OPEN_ID_SERVICE cmp=com.heytap.openid/.IdentifyService } U=0: not found
09-03 14:11:40.592 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:40.592 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:42.117 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:42.117 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:43.594 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:43.594 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:45.141 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:45.141 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:46.625 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:46.625 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:48.121 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:48.122 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:49.683 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 14:11:51.143 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:51.143 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:52.599 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:52.599 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:54.130 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:54.131 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:55.639 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:55.639 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:57.121 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:57.121 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:58.628 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:11:58.629 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:00.112 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:00.112 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:01.639 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:01.639 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:03.140 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:03.140 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:04.629 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:04.630 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:06.118 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:06.119 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:07.634 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:07.634 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:09.144 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:09.144 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:10.629 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:10.629 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:12.119 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:12.119 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:13.622 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:13.622 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:15.155 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:15.155 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:16.637 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:16.637 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:18.131 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:18.132 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:19.252 E/WifiHAL (  284): wifi_get_logger_supported_feature_set: Error -3 happened. 
09-03 14:12:19.254 E/WifiVendorHal(  620): getSupportedFeatureSet(l.891) failed {.code = ERROR_NOT_SUPPORTED, .description = }
09-03 14:12:19.256 E/WifiHAL (  284): wifi_get_logger_supported_feature_set: Error -3 happened. 
09-03 14:12:19.262 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=android.intent.action.ACTION_POWER_CONNECTED flg=0x4000010 (has extras) } to com.tencent.android.qqdownloader/com.qq.AppService.MainReceiver
09-03 14:12:19.262 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=android.intent.action.ACTION_POWER_CONNECTED flg=0x4000010 (has extras) } to com.shinyv.cnr/com.igexin.sdk.PushReceiver
09-03 14:12:19.275 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for wifi
09-03 14:12:19.276 E/BatteryExternalStatsWorker(  620): no controller energy info supplied for bluetooth
09-03 14:12:19.302 E/BatteryExternalStatsWorker(  620): modem info is invalid: ModemActivityInfo{ mTimestamp=0 mSleepTimeMs=0 mIdleTimeMs=0 mTxTimeMs[]=[0, 0, 0, 0, 0] mRxTimeMs=0 mEnergyUsed=0}
09-03 14:12:19.587 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:19.587 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:19.842 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 14:12:19.844 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 14:12:19.850 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 14:12:20.846 W/Tinker.TinkerLoader(19831): tryLoadPatchFiles:patch dir not exist:/data/user/0/com.tencent.qqpimsecure/tinker
09-03 14:12:20.858 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 14:12:20.907 E/zygote  (19831): No implementation found for void com.tencent.wcdb.database.SQLiteGlobal.nativeTestJNIRegistration() (tried Java_com_tencent_wcdb_database_SQLiteGlobal_nativeTestJNIRegistration and Java_com_tencent_wcdb_database_SQLiteGlobal_nativeTestJNIRegistration__)
09-03 14:12:20.989 W/ActivityManager(  620): Permission Denial: opening provider com.android.providers.contacts.ContactsProvider2 from ProcessRecord{ee0c881 19831:com.tencent.qqpimsecure/u0a77} (pid=19831, uid=10077) requires android.permission.READ_CONTACTS or android.permission.WRITE_CONTACTS
09-03 14:12:20.989 W/System.err(19831): java.lang.SecurityException: Permission Denial: opening provider com.android.providers.contacts.ContactsProvider2 from ProcessRecord{ee0c881 19831:com.tencent.qqpimsecure/u0a77} (pid=19831, uid=10077) requires android.permission.READ_CONTACTS or android.permission.WRITE_CONTACTS
09-03 14:12:20.992 W/System.err(19831): 	at android.os.Parcel.readException(Parcel.java:2005)
09-03 14:12:20.993 W/System.err(19831): 	at android.os.Parcel.readException(Parcel.java:1951)
09-03 14:12:20.993 W/System.err(19831): 	at android.content.IContentService$Stub$Proxy.registerContentObserver(IContentService.java:768)
09-03 14:12:20.993 W/System.err(19831): 	at android.content.ContentResolver.registerContentObserver(ContentResolver.java:1924)
09-03 14:12:20.993 W/System.err(19831): 	at android.content.ContentResolver.registerContentObserver(ContentResolver.java:1913)
09-03 14:12:20.993 W/System.err(19831): 	at tcs.bxf$a.Iw(SourceFile:138)
09-03 14:12:20.993 W/System.err(19831): 	at tcs.bxf.<init>(SourceFile:106)
09-03 14:12:20.993 W/System.err(19831): 	at tcs.bxj.onCreate(SourceFile:55)
09-03 14:12:20.993 W/System.err(19831): 	at tcs.fkp.t(SourceFile:78)
09-03 14:12:20.993 W/System.err(19831): 	at tcs.fkp.s(SourceFile:50)
09-03 14:12:20.993 W/System.err(19831): 	at tcs.bxk.<init>(SourceFile:29)
09-03 14:12:20.993 W/System.err(19831): 	at tcs.aev.c(SourceFile:392)
09-03 14:12:20.993 W/System.err(19831): 	at tcs.aev.b(SourceFile:116)
09-03 14:12:20.993 W/System.err(19831): 	at tcs.aev.j(SourceFile:151)
09-03 14:12:20.993 W/System.err(19831): 	at tcs.aeu$b.o(SourceFile:1203)
09-03 14:12:20.993 W/System.err(19831): 	at tcs.aeu.<init>(SourceFile:147)
09-03 14:12:20.993 W/System.err(19831): 	at tcs.aeu.aI(SourceFile:131)
09-03 14:12:20.993 W/System.err(19831): 	at com.meri.service.monitor.f.c(SourceFile:23)
09-03 14:12:20.993 W/System.err(19831): 	at tcs.cee.arZ(SourceFile:273)
09-03 14:12:20.993 W/System.err(19831): 	at tcs.dye.z(SourceFile:44)
09-03 14:12:20.993 W/System.err(19831): 	at com.tencent.server.base.x.onCreate(SourceFile:822)
09-03 14:12:20.993 W/System.err(19831): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-03 14:12:20.993 W/System.err(19831): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-03 14:12:20.993 W/System.err(19831): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-03 14:12:20.993 W/System.err(19831): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-03 14:12:20.994 W/System.err(19831): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-03 14:12:20.994 W/System.err(19831): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-03 14:12:20.994 W/System.err(19831): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-03 14:12:20.994 W/System.err(19831): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-03 14:12:20.994 W/System.err(19831): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-03 14:12:20.994 W/System.err(19831): 	at android.os.Looper.loop(Looper.java:164)
09-03 14:12:20.994 W/System.err(19831): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-03 14:12:20.994 W/System.err(19831): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 14:12:20.994 W/System.err(19831): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-03 14:12:20.994 W/System.err(19831): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-03 14:12:21.044 W/ActivityManager(  620): Background start not allowed: service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService } to com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService from pid=19831 uid=10077 pkg=com.tencent.qqpimsecure
09-03 14:12:21.045 E/AndroidRuntime(19831): FATAL EXCEPTION: main
09-03 14:12:21.045 E/AndroidRuntime(19831): Process: com.tencent.qqpimsecure, PID: 19831
09-03 14:12:21.045 E/AndroidRuntime(19831): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at android.os.Looper.loop(Looper.java:164)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-03 14:12:21.045 E/AndroidRuntime(19831): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	... 8 more
09-03 14:12:21.045 E/AndroidRuntime(19831): Caused by: java.lang.reflect.UndeclaredThrowableException
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at $Proxy5.init(Unknown Source)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	... 12 more
09-03 14:12:21.045 E/AndroidRuntime(19831): Caused by: java.lang.reflect.InvocationTargetException
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	... 16 more
09-03 14:12:21.045 E/AndroidRuntime(19831): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{7d06bbd u0a77 TRNB idle change:uncached procs:1 seq(0,0,0)}
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at epetrp.b.c(SourceFile:8)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	at epetrp.c.init(SourceFile:1)
09-03 14:12:21.045 E/AndroidRuntime(19831): 	... 19 more
09-03 14:12:21.045 W/System.err(19831): -----------UncaughtException(Base)------------
09-03 14:12:21.045 W/System.err(19831): java.lang.RuntimeException: Unable to create application com.tencent.server.base.RealApplication: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-03 14:12:21.045 W/System.err(19831): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5743)
09-03 14:12:21.045 W/System.err(19831): 	at android.app.ActivityThread.-wrap1(Unknown Source:0)
09-03 14:12:21.045 W/System.err(19831): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1656)
09-03 14:12:21.046 W/System.err(19831): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-03 14:12:21.046 W/System.err(19831): 	at android.os.Looper.loop(Looper.java:164)
09-03 14:12:21.046 W/System.err(19831): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-03 14:12:21.046 W/System.err(19831): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 14:12:21.046 W/System.err(19831): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-03 14:12:21.046 W/System.err(19831): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-03 14:12:21.046 W/System.err(19831): Caused by: com.tencent.tinker.loader.TinkerRuntimeException: Tinker Exception:null
09-03 14:12:21.046 W/System.err(19831): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:104)
09-03 14:12:21.046 W/System.err(19831): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreate(SourceFile:110)
09-03 14:12:21.046 W/System.err(19831): 	at com.tencent.tinker.loader.app.TinkerApplication.onCreate(SourceFile:153)
09-03 14:12:21.046 W/System.err(19831): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1119)
09-03 14:12:21.046 W/System.err(19831): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5740)
09-03 14:12:21.046 W/System.err(19831): 	... 8 more
09-03 14:12:21.046 W/System.err(19831): Caused by: java.lang.reflect.UndeclaredThrowableException
09-03 14:12:21.046 W/System.err(19831): 	at $Proxy5.init(Unknown Source)
09-03 14:12:21.046 W/System.err(19831): 	at com.tencent.server.base.x.onCreate(SourceFile:941)
09-03 14:12:21.046 W/System.err(19831): 	at com.tencent.server.base.QQSecureApplication.onCreate(SourceFile:164)
09-03 14:12:21.046 W/System.err(19831): 	at com.tencent.tinker.entry.TinkerApplicationInlineFence.onCreateImpl_$noinline$(SourceFile:99)
09-03 14:12:21.046 W/System.err(19831): 	... 12 more
09-03 14:12:21.046 W/System.err(19831): Caused by: java.lang.reflect.InvocationTargetException
09-03 14:12:21.046 W/System.err(19831): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 14:12:21.047 W/System.err(19831): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-03 14:12:21.047 W/System.err(19831): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-03 14:12:21.047 W/System.err(19831): 	... 16 more
09-03 14:12:21.047 W/System.err(19831): Caused by: java.lang.IllegalStateException: Not allowed to start service Intent { cmp=com.tencent.qqpimsecure/com.tencent.ep.eventreporter.impl.eventmgr.EventManagerService }: app is in background uid UidRecord{7d06bbd u0a77 TRNB idle change:uncached procs:1 seq(0,0,0)}
09-03 14:12:21.047 W/System.err(19831): 	at android.app.ContextImpl.startServiceCommon(ContextImpl.java:1521)
09-03 14:12:21.047 W/System.err(19831): 	at android.app.ContextImpl.startService(ContextImpl.java:1477)
09-03 14:12:21.047 W/System.err(19831): 	at android.content.ContextWrapper.startService(ContextWrapper.java:650)
09-03 14:12:21.047 W/System.err(19831): 	at com.tencent.ep.eventreporter.impl.eventmgr.a.a(SourceFile:33)
09-03 14:12:21.047 W/System.err(19831): 	at epetrp.b.c(SourceFile:8)
09-03 14:12:21.047 W/System.err(19831): 	at epetrp.c.init(SourceFile:1)
09-03 14:12:21.047 W/System.err(19831): 	... 19 more
09-03 14:12:21.047 W/System.err(19831): ----------------------------------------
09-03 14:12:21.100 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:21.100 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:21.110 W/System.err(19831): java.lang.NoSuchMethodException: lock []
09-03 14:12:21.110 W/System.err(19831): 	at java.lang.Class.getMethod(Class.java:2068)
09-03 14:12:21.110 W/System.err(19831): 	at java.lang.Class.getDeclaredMethod(Class.java:2047)
09-03 14:12:21.110 W/System.err(19831): 	at com.tencent.server.base.z.<init>(SourceFile:53)
09-03 14:12:21.110 W/System.err(19831): 	at meri.pluginsdk.PiDBProvider$2.<init>(SourceFile:298)
09-03 14:12:21.110 W/System.err(19831): 	at meri.pluginsdk.PiDBProvider.getDatabase(SourceFile:298)
09-03 14:12:21.110 W/System.err(19831): 	at meri.pluginsdk.PiDBProvider.query(SourceFile:135)
09-03 14:12:21.110 W/System.err(19831): 	at com.tencent.qqpimsecure.storage.s.a(SourceFile:71)
09-03 14:12:21.111 W/System.err(19831): 	at com.tencent.qqpimsecure.storage.i.query(SourceFile:173)
09-03 14:12:21.111 W/System.err(19831): 	at com.tencent.qqpimsecure.storage.a.createDB(SourceFile:47)
09-03 14:12:21.111 W/System.err(19831): 	at com.tencent.qqpimsecure.dao.n.<init>(SourceFile:140)
09-03 14:12:21.111 W/System.err(19831): 	at com.tencent.qqpimsecure.dao.n.Cs(SourceFile:150)
09-03 14:12:21.111 W/System.err(19831): 	at tcs.ced.arY(SourceFile:308)
09-03 14:12:21.111 W/System.err(19831): 	at skahr.p.aGl(SourceFile:158)
09-03 14:12:21.111 W/System.err(19831): 	at skahr.p.k(SourceFile:83)
09-03 14:12:21.111 W/System.err(19831): 	at skahr.z.hB(SourceFile:84)
09-03 14:12:21.111 W/System.err(19831): 	at skahr.aa.b(SourceFile:1285)
09-03 14:12:21.111 W/System.err(19831): 	at skahr.aa.aHj(SourceFile:991)
09-03 14:12:21.111 W/System.err(19831): 	at skahr.aa.f(SourceFile:59)
09-03 14:12:21.111 W/System.err(19831): 	at skahr.aa$e.l(SourceFile:280)
09-03 14:12:21.111 W/System.err(19831): 	at skahr.i.handleMessage(SourceFile:24)
09-03 14:12:21.111 W/System.err(19831): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-03 14:12:21.111 W/System.err(19831): 	at android.os.Looper.loop(Looper.java:164)
09-03 14:12:21.111 W/System.err(19831): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-03 14:12:22.042 W/seThreadHandler(19861): type=1400 audit(0.0:13388): avc: denied { read } for name="anr" dev="mmcblk0p28" ino=425990 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:anr_data_file:s0 tclass=dir permissive=0
09-03 14:12:22.061 E/linker  (19831): "/data/app/com.tencent.qqpimsecure-Z8_jbw2oAWI1x0G7nnRKaw==/lib/arm/libNativeRQD.so" has text relocations (https://android.googlesource.com/platform/bionic/+/master/android-changes-for-ndk-developers.md#Text-Relocations-Enforced-for-API-level-23)
09-03 14:12:22.066 W/ActivityManager(  620): Background start not allowed: service Intent { cmp=com.tencent.qqpimsecure/com.tencent.server.back.BackEngine } to com.tencent.qqpimsecure/com.tencent.server.back.BackEngine from pid=19831 uid=10077 pkg=com.tencent.qqpimsecure
09-03 14:12:22.087 W/ActivityManager(  620): Unable to start service Intent { act=action.com.heytap.openid.OPEN_ID_SERVICE cmp=com.heytap.openid/.IdentifyService } U=0: not found
09-03 14:12:22.118 W/System.err(19831): java.io.FileNotFoundException: /system/build.prop (Permission denied)
09-03 14:12:22.118 W/System.err(19831): 	at java.io.FileInputStream.open0(Native Method)
09-03 14:12:22.118 W/System.err(19831): 	at java.io.FileInputStream.open(FileInputStream.java:200)
09-03 14:12:22.118 W/System.err(19831): 	at java.io.FileInputStream.<init>(FileInputStream.java:150)
09-03 14:12:22.118 W/System.err(19831): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
09-03 14:12:22.118 W/System.err(19831): 	at java.io.FileReader.<init>(FileReader.java:58)
09-03 14:12:22.118 W/System.err(19831): 	at com.tencent.bugly.crashreport.common.info.c.og(SourceFile:177)
09-03 14:12:22.118 W/System.err(19831): 	at com.tencent.bugly.crashreport.common.info.c.d(SourceFile:226)
09-03 14:12:22.118 W/System.err(19831): 	at com.tencent.bugly.crashreport.common.info.b.og(SourceFile:343)
09-03 14:12:22.118 W/System.err(19831): 	at com.tencent.bugly.crashreport.crash.b.a(SourceFile:973)
09-03 14:12:22.118 W/System.err(19831): 	at com.tencent.bugly.crashreport.crash.b.a(SourceFile:1228)
09-03 14:12:22.118 W/System.err(19831): 	at com.tencent.bugly.crashreport.crash.b.a(SourceFile:413)
09-03 14:12:22.118 W/System.err(19831): 	at com.tencent.bugly.crashreport.crash.c$2.run(SourceFile:323)
09-03 14:12:22.118 W/System.err(19831): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:457)
09-03 14:12:22.118 W/System.err(19831): 	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
09-03 14:12:22.118 W/System.err(19831): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:301)
09-03 14:12:22.118 W/System.err(19831): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1162)
09-03 14:12:22.118 W/System.err(19831): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:636)
09-03 14:12:22.118 W/System.err(19831): 	at java.lang.Thread.run(Thread.java:764)
09-03 14:12:22.157 W/ActivityManager(  620): Background start not allowed: service Intent { act=com.tencent.server.fore.ForeService pkg=com.tencent.qqpimsecure (has extras) } to com.tencent.qqpimsecure/com.tencent.server.fore.ForeService from pid=19831 uid=10077 pkg=com.tencent.qqpimsecure
09-03 14:12:22.166 W/ActivityManager(  620): Background start not allowed: service Intent { act=com.tencent.server.fore.ForeService pkg=com.tencent.qqpimsecure (has extras) } to com.tencent.qqpimsecure/com.tencent.server.fore.ForeService from pid=19831 uid=10077 pkg=com.tencent.qqpimsecure
09-03 14:12:22.171 W/ActivityManager(  620): Background start not allowed: service Intent { act=com.tencent.server.fore.ForeService pkg=com.tencent.qqpimsecure (has extras) } to com.tencent.qqpimsecure/com.tencent.server.fore.ForeService from pid=19831 uid=10077 pkg=com.tencent.qqpimsecure
09-03 14:12:22.272 W/TuringMMWorker(19937): type=1400 audit(0.0:13389): avc: denied { getattr } for path="/system/bin/install-recovery.sh" dev="mmcblk0p14" ino=264 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:install_recovery_exec:s0 tclass=file permissive=0
09-03 14:12:22.272 W/TuringMMWorker(19937): type=1400 audit(0.0:13390): avc: denied { read } for name="enforce" dev="selinuxfs" ino=4 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:selinuxfs:s0 tclass=file permissive=0
09-03 14:12:22.279 W/BUGLY_THREAD(19910): type=1400 audit(0.0:13391): avc: denied { read } for name="type" dev="sysfs" ino=18777 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:sysfs:s0 tclass=file permissive=0
09-03 14:12:22.435 W/BUGLY_THREAD(19910): type=1400 audit(0.0:13392): avc: denied { search } for name="usb" dev="sysfs" ino=14413 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:sysfs_usb_supply:s0 tclass=dir permissive=0
09-03 14:12:22.435 W/BUGLY_THREAD(19910): type=1400 audit(0.0:13393): avc: denied { read } for name="capacity" dev="sysfs" ino=18538 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:sysfs:s0 tclass=file permissive=0
09-03 14:12:22.502 W/BUGLY_THREAD(19910): type=1400 audit(0.0:13394): avc: denied { read } for name="uptime" dev="proc" ino=4026542453 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:proc:s0 tclass=file permissive=0
09-03 14:12:22.589 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:22.589 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:24.039 W/Shark-Looper-TM(19859): type=1400 audit(0.0:13395): avc: denied { read } for name="version" dev="proc" ino=4026542454 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:proc:s0 tclass=file permissive=0
09-03 14:12:24.039 W/Shark-Looper-TM(19859): type=1400 audit(0.0:13396): avc: denied { read } for name="type" dev="sysfs" ino=18777 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:sysfs:s0 tclass=file permissive=0
09-03 14:12:24.085 W/Shark-Looper-TM(19859): type=1400 audit(0.0:13397): avc: denied { read } for name="version" dev="proc" ino=4026542454 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:proc:s0 tclass=file permissive=0
09-03 14:12:24.085 W/Shark-Looper-TM(19859): type=1400 audit(0.0:13398): avc: denied { read } for name="type" dev="sysfs" ino=18777 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:sysfs:s0 tclass=file permissive=0
09-03 14:12:24.093 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:24.093 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:25.072 W/ActivityManager(  620): Background start not allowed: service Intent { cmp=com.tencent.qqpimsecure/com.tencent.server.back.BackEngine } to com.tencent.qqpimsecure/com.tencent.server.back.BackEngine from pid=19831 uid=10077 pkg=com.tencent.qqpimsecure
09-03 14:12:25.637 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:25.638 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:26.021 E/AndroidRuntime(19831): FATAL EXCEPTION: com.tencent.meri-BaseThreadHandler
09-03 14:12:26.021 E/AndroidRuntime(19831): Process: com.tencent.qqpimsecure, PID: 19831
09-03 14:12:26.021 E/AndroidRuntime(19831): java.lang.InternalError: Thread starting during runtime shutdown
09-03 14:12:26.021 E/AndroidRuntime(19831): 	at java.lang.Thread.nativeCreate(Native Method)
09-03 14:12:26.021 E/AndroidRuntime(19831): 	at java.lang.Thread.start(Thread.java:733)
09-03 14:12:26.021 E/AndroidRuntime(19831): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-03 14:12:26.021 E/AndroidRuntime(19831): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-03 14:12:26.021 E/AndroidRuntime(19831): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-03 14:12:26.021 E/AndroidRuntime(19831): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-03 14:12:26.021 E/AndroidRuntime(19831): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-03 14:12:26.021 E/AndroidRuntime(19831): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-03 14:12:26.021 E/AndroidRuntime(19831): 	at tcs.bca.<init>(SourceFile:24)
09-03 14:12:26.021 E/AndroidRuntime(19831): 	at tcs.bcb.dv(SourceFile:157)
09-03 14:12:26.021 E/AndroidRuntime(19831): 	at tcs.bcb.b(SourceFile:135)
09-03 14:12:26.021 E/AndroidRuntime(19831): 	at tcs.bcb.uF(SourceFile:229)
09-03 14:12:26.021 E/AndroidRuntime(19831): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-03 14:12:26.021 E/AndroidRuntime(19831): 	at android.os.Handler.handleCallback(Handler.java:790)
09-03 14:12:26.021 E/AndroidRuntime(19831): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-03 14:12:26.021 E/AndroidRuntime(19831): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-03 14:12:26.021 E/AndroidRuntime(19831): 	at android.os.Looper.loop(Looper.java:164)
09-03 14:12:26.021 E/AndroidRuntime(19831): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-03 14:12:26.021 E/AndroidRuntime(19831): 	at tcs.alk.run(SourceFile:79)
09-03 14:12:26.048 E/AndroidRuntime(19831): FATAL EXCEPTION: com.tencent.meri-ep_monitor
09-03 14:12:26.048 E/AndroidRuntime(19831): Process: com.tencent.qqpimsecure, PID: 19831
09-03 14:12:26.048 E/AndroidRuntime(19831): java.lang.reflect.UndeclaredThrowableException
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at $Proxy6.getPreferenceService(Unknown Source)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at epmt.j.c(SourceFile:1)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at epmt.c.a(SourceFile:2)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at epmt.g.l(SourceFile:99)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at epmt.g.a(SourceFile:2)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at epmt.g$c.handleMessage(SourceFile:1)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at android.os.Looper.loop(Looper.java:164)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at tcs.alk.run(SourceFile:79)
09-03 14:12:26.048 E/AndroidRuntime(19831): Caused by: java.lang.reflect.InvocationTargetException
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at epfrwcore.a$a.invoke(SourceFile:1)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at java.lang.reflect.Proxy.invoke(Proxy.java:913)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	... 10 more
09-03 14:12:26.048 E/AndroidRuntime(19831): Caused by: java.lang.InternalError: Thread starting during runtime shutdown
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at java.lang.Thread.nativeCreate(Native Method)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at java.lang.Thread.start(Thread.java:733)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at tcs.eiv.aq(SourceFile:111)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at com.tencent.qqpimsecure.storage.x.C(SourceFile:263)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at com.tencent.qqpimsecure.storage.y.aw(SourceFile:50)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at tcs.ahr.<init>(SourceFile:16)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	at tcs.ahn.getPreferenceService(SourceFile:54)
09-03 14:12:26.048 E/AndroidRuntime(19831): 	... 13 more
09-03 14:12:26.473 W/ProcessCpuTracker(  620): Skipping unknown process pid 20033
09-03 14:12:26.535 W/seThreadHandler(19861): type=1400 audit(0.0:13399): avc: denied { read } for name="type" dev="sysfs" ino=18777 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:sysfs:s0 tclass=file permissive=0
09-03 14:12:26.535 W/seThreadHandler(19861): type=1400 audit(0.0:13400): avc: denied { search } for name="usb" dev="sysfs" ino=14413 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:sysfs_usb_supply:s0 tclass=dir permissive=0
09-03 14:12:26.535 W/seThreadHandler(19861): type=1400 audit(0.0:13401): avc: denied { read } for name="capacity" dev="sysfs" ino=18538 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:sysfs:s0 tclass=file permissive=0
09-03 14:12:26.539 W/seThreadHandler(19861): type=1400 audit(0.0:13402): avc: denied { read } for name="uptime" dev="proc" ino=4026542453 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:proc:s0 tclass=file permissive=0
09-03 14:12:26.542 W/System.err(19831): java.lang.InternalError: Thread starting during runtime shutdown
09-03 14:12:26.542 W/System.err(19831): 	at java.lang.Thread.nativeCreate(Native Method)
09-03 14:12:26.542 W/System.err(19831): 	at java.lang.Thread.start(Thread.java:733)
09-03 14:12:26.542 W/System.err(19831): 	at com.tencent.bugly.proguard.ak.a(SourceFile:713)
09-03 14:12:26.542 W/System.err(19831): 	at com.tencent.bugly.proguard.ak.a(SourceFile:751)
09-03 14:12:26.542 W/System.err(19831): 	at com.tencent.bugly.proguard.ak.a(SourceFile:311)
09-03 14:12:26.542 W/System.err(19831): 	at com.tencent.bugly.crashreport.crash.b.a(SourceFile:451)
09-03 14:12:26.542 W/System.err(19831): 	at com.tencent.bugly.crashreport.crash.b.a(SourceFile:386)
09-03 14:12:26.542 W/System.err(19831): 	at com.tencent.bugly.crashreport.crash.d.b(SourceFile:331)
09-03 14:12:26.542 W/System.err(19831): 	at com.tencent.bugly.crashreport.crash.d.uncaughtException(SourceFile:384)
09-03 14:12:26.543 W/System.err(19831): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:1068)
09-03 14:12:26.543 W/System.err(19831): 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:1063)
09-03 14:12:26.543 W/System.err(19831): 	at java.lang.Thread.dispatchUncaughtException(Thread.java:1955)
09-03 14:12:26.543 W/System.err(19831): -----------UncaughtException(Base)------------
09-03 14:12:26.543 W/System.err(19831): java.lang.InternalError: Thread starting during runtime shutdown
09-03 14:12:26.543 W/System.err(19831): 	at java.lang.Thread.nativeCreate(Native Method)
09-03 14:12:26.543 W/System.err(19831): 	at java.lang.Thread.start(Thread.java:733)
09-03 14:12:26.543 W/System.err(19831): 	at android.app.SharedPreferencesImpl.startLoadFromDisk(SharedPreferencesImpl.java:119)
09-03 14:12:26.543 W/System.err(19831): 	at android.app.SharedPreferencesImpl.<init>(SharedPreferencesImpl.java:112)
09-03 14:12:26.543 W/System.err(19831): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:391)
09-03 14:12:26.543 W/System.err(19831): 	at android.app.ContextImpl.getSharedPreferences(ContextImpl.java:372)
09-03 14:12:26.543 W/System.err(19831): 	at android.content.ContextWrapper.getSharedPreferences(ContextWrapper.java:167)
09-03 14:12:26.543 W/System.err(19831): 	at com.tencent.qqpimsecure.storage.l.<init>(SourceFile:43)
09-03 14:12:26.543 W/System.err(19831): 	at tcs.bca.<init>(SourceFile:24)
09-03 14:12:26.543 W/System.err(19831): 	at tcs.bcb.dv(SourceFile:157)
09-03 14:12:26.543 W/System.err(19831): 	at tcs.bcb.b(SourceFile:135)
09-03 14:12:26.543 W/System.err(19831): 	at tcs.bcb.uF(SourceFile:229)
09-03 14:12:26.543 W/System.err(19831): 	at com.tencent.server.base.x$6.run(SourceFile:1480)
09-03 14:12:26.543 W/System.err(19831): 	at android.os.Handler.handleCallback(Handler.java:790)
09-03 14:12:26.543 W/System.err(19831): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-03 14:12:26.543 W/System.err(19831): 	at meri.util.l.dispatchMessage(SourceFile:50)
09-03 14:12:26.543 W/System.err(19831): 	at android.os.Looper.loop(Looper.java:164)
09-03 14:12:26.543 W/System.err(19831): 	at android.os.HandlerThread.run(HandlerThread.java:65)
09-03 14:12:26.543 W/System.err(19831): 	at tcs.alk.run(SourceFile:79)
09-03 14:12:26.543 W/System.err(19831): ----------------------------------------
09-03 14:12:26.558 W/zygote  (19831): Long monitor contention with owner com.tencent.meri-BaseThreadHandler (19861) at int libcore.io.Linux.readBytes(java.io.FileDescriptor, java.lang.Object, int, int)(Linux.java:-2) waiters=0 in void com.tencent.bugly.crashreport.crash.d.uncaughtException(java.lang.Thread, java.lang.Throwable) for 509ms
09-03 14:12:26.577 W/ActivityManager(  620): Scheduling restart of crashed service com.tencent.qqpimsecure/com.tencent.server.back.SyncTaskService in 1000ms
09-03 14:12:26.577 W/zygote  (  620): kill(-19831, 9) failed: No such process
09-03 14:12:26.618 W/zygote  (  620): kill(-19831, 9) failed: No such process
09-03 14:12:27.140 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:27.140 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:28.626 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:28.626 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:30.121 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:30.121 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:31.624 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:31.624 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:33.143 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:33.143 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:34.631 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:34.632 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:35.575 W/System.err(19529): java.lang.reflect.InvocationTargetException
09-03 14:12:35.575 W/System.err(19529): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 14:12:35.575 W/System.err(19529): 	at com.linker.xlyt.Api.ad.ADApi.getIMEI(ADApi.java:134)
09-03 14:12:35.575 W/System.err(19529): 	at com.linker.xlyt.Api.ad.ADApi$1.addParams(ADApi.java:88)
09-03 14:12:35.575 W/System.err(19529): 	at com.hzlh.sdk.net.HttpMap.getMap(HttpMap.java:20)
09-03 14:12:35.575 W/System.err(19529): 	at com.linker.xlyt.Api.ad.ADApi.getAd(ADApi.java:80)
09-03 14:12:35.575 W/System.err(19529): 	at com.linker.xlyt.Api.ad.ADApi.getAd(ADApi.java:55)
09-03 14:12:35.575 W/System.err(19529): 	at com.shinyv.cnr.StartActivity.initApp(StartActivity.java:550)
09-03 14:12:35.575 W/System.err(19529): 	at com.shinyv.cnr.StartActivity.lambda$new$0$StartActivity(StartActivity.java:173)
09-03 14:12:35.575 W/System.err(19529): 	at com.shinyv.cnr.-$$Lambda$StartActivity$a_Z0bPlPEBZBKBG6_FVbGkcY9Tc.handleMessage(Unknown Source:2)
09-03 14:12:35.575 W/System.err(19529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-03 14:12:35.576 W/System.err(19529): 	at android.os.Looper.loop(Looper.java:164)
09-03 14:12:35.576 W/System.err(19529): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-03 14:12:35.576 W/System.err(19529): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 14:12:35.576 W/System.err(19529): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-03 14:12:35.576 W/System.err(19529): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-03 14:12:35.576 W/System.err(19529): Caused by: java.lang.SecurityException: getImeiForSlot: Neither user 11139 nor current process has android.permission.READ_PHONE_STATE.
09-03 14:12:35.576 W/System.err(19529): 	at android.os.Parcel.readException(Parcel.java:2005)
09-03 14:12:35.576 W/System.err(19529): 	at android.os.Parcel.readException(Parcel.java:1951)
09-03 14:12:35.576 W/System.err(19529): 	at com.android.internal.telephony.ITelephony$Stub$Proxy.getImeiForSlot(ITelephony.java:4977)
09-03 14:12:35.576 W/System.err(19529): 	at android.telephony.TelephonyManager.getImei(TelephonyManager.java:1076)
09-03 14:12:35.576 W/System.err(19529): 	at android.telephony.TelephonyManager.getImei(TelephonyManager.java:1061)
09-03 14:12:35.576 W/System.err(19529): 	... 15 more
09-03 14:12:35.576 E/YLog    (19529): getIMEI??????0d80afaa50913110
09-03 14:12:35.667 W/Adreno-EGL(19529): <qeglDrvAPI_eglGetConfigAttrib:607>: EGL_BAD_ATTRIBUTE
09-03 14:12:35.671 W/Adreno-EGL(19529): <qeglDrvAPI_eglGetConfigAttrib:607>: EGL_BAD_ATTRIBUTE
09-03 14:12:35.735 W/work_thread(20070): type=1400 audit(0.0:13403): avc: denied { read } for name="boot_id" dev="proc" ino=3144719 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:proc:s0 tclass=file permissive=0
09-03 14:12:35.745 W/ZIDThreadPoolEx(20071): type=1400 audit(0.0:13404): avc: denied { read } for name="boot_id" dev="proc" ino=3144719 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:proc:s0 tclass=file permissive=0
09-03 14:12:35.758 W/ResourceType(19529): No package identifier when getting value for resource number 0x00000000
09-03 14:12:35.758 W/System.err(19529): android.content.res.Resources$NotFoundException: String resource ID #0x0
09-03 14:12:35.758 W/System.err(19529): 	at android.content.res.Resources.getText(Resources.java:339)
09-03 14:12:35.758 W/System.err(19529): 	at android.content.res.Resources.getString(Resources.java:433)
09-03 14:12:35.758 W/System.err(19529): 	at com.umeng.umzid.ZIDManager.a(:21)
09-03 14:12:35.758 W/System.err(19529): 	at com.umeng.umzid.ZIDManager.b(:5)
09-03 14:12:35.758 W/System.err(19529): 	at com.umeng.umzid.ZIDManager$d.run(Unknown Source:4)
09-03 14:12:35.758 W/System.err(19529): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:457)
09-03 14:12:35.758 W/System.err(19529): 	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
09-03 14:12:35.758 W/System.err(19529): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:301)
09-03 14:12:35.759 W/System.err(19529): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1162)
09-03 14:12:35.759 W/System.err(19529): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:636)
09-03 14:12:35.759 W/System.err(19529): 	at java.lang.Thread.run(Thread.java:764)
09-03 14:12:35.889 W/work_thread(20078): type=1400 audit(0.0:13405): avc: denied { read } for name="boot_id" dev="proc" ino=3144719 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:proc:s0 tclass=file permissive=0
09-03 14:12:36.091 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:36.091 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:37.625 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:37.626 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:38.940 E/Avrcp   ( 2084): play status change 0???0 mPlayStatusChangedNT: 1
09-03 14:12:38.940 E/Avrcp   ( 2084): play status change 0???0 mPlayStatusChangedNT: 1
09-03 14:12:38.945 W/Avrcp   ( 2084): playState object null, sending STOPPED
09-03 14:12:38.948 W/Avrcp   ( 2084): playState object null, sending STOPPED
09-03 14:12:38.963 E/Avrcp   ( 2084): play status change 0???0 mPlayStatusChangedNT: 1
09-03 14:12:38.965 E/Avrcp   ( 2084): play status change 0???0 mPlayStatusChangedNT: 1
09-03 14:12:38.967 E/Avrcp   ( 2084): play status change 0???0 mPlayStatusChangedNT: 1
09-03 14:12:39.070 W/LOTTIE  (19529): Animation contains merge paths. Merge paths are only supported on KitKat+ and must be manually enabled by calling enableMergePathsForKitKatAndAbove().
09-03 14:12:39.111 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:39.112 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:39.246 E/bt_btm  ( 2084): BD Address not found!
09-03 14:12:39.246 E/bt_btif ( 2084): bte_scan_filt_param_cfg_evt, 1
09-03 14:12:39.246 W/bt_btif ( 2084): bta_dm_check_av:0
09-03 14:12:39.250 E/bt_btm  ( 2084): btm_flt_update_cb: bad length: 1
09-03 14:12:39.465 W/BroadcastQueue(  620): Permission Denial: receiving Intent { act=android.bluetooth.device.action.FOUND flg=0x10 (has extras) } to ProcessRecord{c27c6b3 9430:com.shinyv.cnr:pushservice/u0a1139} (pid=9430, uid=11139) requires android.permission.ACCESS_COARSE_LOCATION due to sender com.android.bluetooth (uid 1002)
09-03 14:12:39.505 W/System.err(19529): java.lang.reflect.InvocationTargetException
09-03 14:12:39.505 W/System.err(19529): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 14:12:39.505 W/System.err(19529): 	at com.linker.xlyt.Api.ad.ADApi.getIMEI(ADApi.java:134)
09-03 14:12:39.505 W/System.err(19529): 	at com.linker.xlyt.Api.ad.ADApi$1.addParams(ADApi.java:88)
09-03 14:12:39.505 W/System.err(19529): 	at com.hzlh.sdk.net.HttpMap.getMap(HttpMap.java:20)
09-03 14:12:39.505 W/System.err(19529): 	at com.linker.xlyt.Api.ad.ADApi.getAd(ADApi.java:80)
09-03 14:12:39.505 W/System.err(19529): 	at com.linker.xlyt.Api.ad.ADApi.getAd(ADApi.java:55)
09-03 14:12:39.505 W/System.err(19529): 	at com.linker.xlyt.module.home.HomeFragment.requestAd(HomeFragment.java:1157)
09-03 14:12:39.505 W/System.err(19529): 	at com.linker.xlyt.module.home.HomeFragment.init(HomeFragment.java:268)
09-03 14:12:39.505 W/System.err(19529): 	at com.linker.xlyt.module.play.fragment.BaseInitFragment.onStart(BaseInitFragment.java:65)
09-03 14:12:39.505 W/System.err(19529): 	at androidx.fragment.app.Fragment.performStart(Fragment.java:2730)
09-03 14:12:39.505 W/System.err(19529): 	at androidx.fragment.app.FragmentStateManager.start(FragmentStateManager.java:355)
09-03 14:12:39.505 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.moveToState(FragmentManager.java:1192)
09-03 14:12:39.505 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.moveToState(FragmentManager.java:1354)
09-03 14:12:39.505 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.moveFragmentToExpectedState(FragmentManager.java:1432)
09-03 14:12:39.505 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.moveToState(FragmentManager.java:1495)
09-03 14:12:39.505 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.dispatchStateChange(FragmentManager.java:2617)
09-03 14:12:39.505 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.dispatchStart(FragmentManager.java:2575)
09-03 14:12:39.505 W/System.err(19529): 	at androidx.fragment.app.FragmentController.dispatchStart(FragmentController.java:258)
09-03 14:12:39.505 W/System.err(19529): 	at androidx.fragment.app.FragmentActivity.onStart(FragmentActivity.java:550)
09-03 14:12:39.505 W/System.err(19529): 	at androidx.appcompat.app.AppCompatActivity.onStart(AppCompatActivity.java:210)
09-03 14:12:39.505 W/System.err(19529): 	at android.app.Instrumentation.callActivityOnStart(Instrumentation.java:1334)
09-03 14:12:39.505 W/System.err(19529): 	at android.app.Activity.performStart(Activity.java:7029)
09-03 14:12:39.505 W/System.err(19529): 	at android.app.ActivityThread.performLaunchActivity(ActivityThread.java:2741)
09-03 14:12:39.506 W/System.err(19529): 	at android.app.ActivityThread.handleLaunchActivity(ActivityThread.java:2856)
09-03 14:12:39.506 W/System.err(19529): 	at android.app.ActivityThread.-wrap11(Unknown Source:0)
09-03 14:12:39.506 W/System.err(19529): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1589)
09-03 14:12:39.506 W/System.err(19529): 	at android.os.Handler.dispatchMessage(Handler.java:106)
09-03 14:12:39.506 W/System.err(19529): 	at android.os.Looper.loop(Looper.java:164)
09-03 14:12:39.506 W/System.err(19529): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-03 14:12:39.506 W/System.err(19529): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 14:12:39.506 W/System.err(19529): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-03 14:12:39.506 W/System.err(19529): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-03 14:12:39.506 W/System.err(19529): Caused by: java.lang.SecurityException: getImeiForSlot: Neither user 11139 nor current process has android.permission.READ_PHONE_STATE.
09-03 14:12:39.506 W/System.err(19529): 	at android.os.Parcel.readException(Parcel.java:2005)
09-03 14:12:39.506 W/System.err(19529): 	at android.os.Parcel.readException(Parcel.java:1951)
09-03 14:12:39.506 W/System.err(19529): 	at com.android.internal.telephony.ITelephony$Stub$Proxy.getImeiForSlot(ITelephony.java:4977)
09-03 14:12:39.506 W/System.err(19529): 	at android.telephony.TelephonyManager.getImei(TelephonyManager.java:1076)
09-03 14:12:39.506 W/System.err(19529): 	at android.telephony.TelephonyManager.getImei(TelephonyManager.java:1061)
09-03 14:12:39.506 W/System.err(19529): 	... 32 more
09-03 14:12:39.507 E/YLog    (19529): getIMEI??????0d80afaa50913110
09-03 14:12:39.581 W/Avrcp   ( 2084): playState object null, sending STOPPED
09-03 14:12:39.583 E/Avrcp   ( 2084): play status change 0???0 mPlayStatusChangedNT: 1
09-03 14:12:39.583 E/Avrcp   ( 2084): play status change 0???0 mPlayStatusChangedNT: 1
09-03 14:12:39.584 W/Avrcp   ( 2084): playState object null, sending STOPPED
09-03 14:12:39.585 E/Avrcp   ( 2084): play status change 0???0 mPlayStatusChangedNT: 1
09-03 14:12:39.587 E/Avrcp   ( 2084): play status change 0???0 mPlayStatusChangedNT: 1
09-03 14:12:39.587 E/Avrcp   ( 2084): play status change 0???0 mPlayStatusChangedNT: 1
09-03 14:12:39.587 W/Avrcp   ( 2084): playState object null, sending STOPPED
09-03 14:12:39.589 E/Avrcp   ( 2084): play status change 0???0 mPlayStatusChangedNT: 1
09-03 14:12:39.589 E/Avrcp   ( 2084): play status change 0???0 mPlayStatusChangedNT: 1
09-03 14:12:39.592 W/Avrcp   ( 2084): playState object null, sending STOPPED
09-03 14:12:39.594 E/Avrcp   ( 2084): play status change 0???0 mPlayStatusChangedNT: 1
09-03 14:12:39.595 E/Avrcp   ( 2084): play status change 0???0 mPlayStatusChangedNT: 1
09-03 14:12:39.645 W/LOTTIE  (19529): Animation contains merge paths but they are disabled.
09-03 14:12:39.944 W/bt_btm_ble( 2084): btm_ble_process_adv_pkt_cont device no longer discoverable, discarding advertising packet
09-03 14:12:39.952 W/System.err(19529): java.lang.reflect.InvocationTargetException
09-03 14:12:39.953 W/System.err(19529): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 14:12:39.953 W/System.err(19529): 	at com.linker.xlyt.Api.ad.ADApi.getIMEI(ADApi.java:134)
09-03 14:12:39.953 W/System.err(19529): 	at com.linker.xlyt.Api.ad.ADApi$1.addParams(ADApi.java:88)
09-03 14:12:39.953 W/System.err(19529): 	at com.hzlh.sdk.net.HttpMap.getMap(HttpMap.java:20)
09-03 14:12:39.954 W/System.err(19529): 	at com.linker.xlyt.Api.ad.ADApi.getAd(ADApi.java:80)
09-03 14:12:39.954 W/System.err(19529): 	at com.linker.xlyt.Api.ad.ADApi.getAd(ADApi.java:55)
09-03 14:12:39.954 W/System.err(19529): 	at com.linker.xlyt.module.newHome.ListenTVFragment.loadDate(ListenTVFragment.java:1098)
09-03 14:12:39.954 W/System.err(19529): 	at com.linker.xlyt.module.newHome.ListenTVFragment.init(ListenTVFragment.java:890)
09-03 14:12:39.954 W/System.err(19529): 	at com.linker.xlyt.module.play.fragment.BaseInitFragment.onStart(BaseInitFragment.java:65)
09-03 14:12:39.954 W/System.err(19529): 	at androidx.fragment.app.Fragment.performStart(Fragment.java:2730)
09-03 14:12:39.954 W/System.err(19529): 	at androidx.fragment.app.FragmentStateManager.start(FragmentStateManager.java:355)
09-03 14:12:39.954 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.moveToState(FragmentManager.java:1192)
09-03 14:12:39.954 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.moveToState(FragmentManager.java:1354)
09-03 14:12:39.954 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.moveFragmentToExpectedState(FragmentManager.java:1432)
09-03 14:12:39.954 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.moveToState(FragmentManager.java:1495)
09-03 14:12:39.954 W/System.err(19529): 	at androidx.fragment.app.BackStackRecord.executeOps(BackStackRecord.java:447)
09-03 14:12:39.954 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.executeOps(FragmentManager.java:2167)
09-03 14:12:39.954 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.executeOpsTogether(FragmentManager.java:1990)
09-03 14:12:39.954 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.removeRedundantOperationsAndExecute(FragmentManager.java:1945)
09-03 14:12:39.954 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.execSingleAction(FragmentManager.java:1816)
09-03 14:12:39.954 W/System.err(19529): 	at androidx.fragment.app.BackStackRecord.commitNowAllowingStateLoss(BackStackRecord.java:303)
09-03 14:12:39.954 W/System.err(19529): 	at androidx.fragment.app.FragmentStatePagerAdapter.finishUpdate(FragmentStatePagerAdapter.java:262)
09-03 14:12:39.954 W/System.err(19529): 	at androidx.viewpager.widget.ViewPager.populate(ViewPager.java:1244)
09-03 14:12:39.954 W/System.err(19529): 	at androidx.viewpager.widget.ViewPager.populate(ViewPager.java:1092)
09-03 14:12:39.954 W/System.err(19529): 	at androidx.viewpager.widget.ViewPager.onMeasure(ViewPager.java:1622)
09-03 14:12:39.954 W/System.err(19529): 	at com.linker.xlyt.view.InnerViewPager.onMeasure(InnerViewPager.java:110)
09-03 14:12:39.954 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:39.954 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:39.954 W/System.err(19529): 	at android.widget.LinearLayout.measureChildBeforeLayout(LinearLayout.java:1514)
09-03 14:12:39.954 W/System.err(19529): 	at android.widget.LinearLayout.measureVertical(LinearLayout.java:806)
09-03 14:12:39.954 W/System.err(19529): 	at android.widget.LinearLayout.onMeasure(LinearLayout.java:685)
09-03 14:12:39.954 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:39.954 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:39.954 W/System.err(19529): 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:185)
09-03 14:12:39.954 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:39.954 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:39.955 W/System.err(19529): 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:185)
09-03 14:12:39.955 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:39.955 W/System.err(19529): 	at android.widget.RelativeLayout.measureChildHorizontal(RelativeLayout.java:715)
09-03 14:12:39.955 W/System.err(19529): 	at android.widget.RelativeLayout.onMeasure(RelativeLayout.java:461)
09-03 14:12:39.955 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:39.955 W/System.err(19529): 	at android.widget.RelativeLayout.measureChildHorizontal(RelativeLayout.java:715)
09-03 14:12:39.955 W/System.err(19529): 	at android.widget.RelativeLayout.onMeasure(RelativeLayout.java:461)
09-03 14:12:39.955 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:39.955 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:39.955 W/System.err(19529): 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:185)
09-03 14:12:39.955 W/System.err(19529): 	at androidx.appcompat.widget.ContentFrameLayout.onMeasure(ContentFrameLayout.java:146)
09-03 14:12:39.955 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:39.955 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:39.955 W/System.err(19529): 	at android.widget.LinearLayout.measureChildBeforeLayout(LinearLayout.java:1514)
09-03 14:12:39.955 W/System.err(19529): 	at android.widget.LinearLayout.measureVertical(LinearLayout.java:806)
09-03 14:12:39.955 W/System.err(19529): 	at android.widget.LinearLayout.onMeasure(LinearLayout.java:685)
09-03 14:12:39.955 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:39.955 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:39.955 W/System.err(19529): 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:185)
09-03 14:12:39.955 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:39.955 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:39.955 W/System.err(19529): 	at android.widget.LinearLayout.measureChildBeforeLayout(LinearLayout.java:1514)
09-03 14:12:39.955 W/System.err(19529): 	at android.widget.LinearLayout.measureVertical(LinearLayout.java:806)
09-03 14:12:39.955 W/System.err(19529): 	at android.widget.LinearLayout.onMeasure(LinearLayout.java:685)
09-03 14:12:39.955 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:39.955 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:39.955 W/System.err(19529): 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:185)
09-03 14:12:39.955 W/System.err(19529): 	at com.android.internal.policy.DecorView.onMeasure(DecorView.java:724)
09-03 14:12:39.955 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:39.955 W/System.err(19529): 	at android.view.ViewRootImpl.performMeasure(ViewRootImpl.java:2422)
09-03 14:12:39.955 W/System.err(19529): 	at android.view.ViewRootImpl.measureHierarchy(ViewRootImpl.java:1504)
09-03 14:12:39.955 W/System.err(19529): 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:1761)
09-03 14:12:39.955 W/System.err(19529): 	at android.view.ViewRootImpl.doTraversal(ViewRootImpl.java:1392)
09-03 14:12:39.955 W/System.err(19529): 	at android.view.ViewRootImpl$TraversalRunnable.run(ViewRootImpl.java:6752)
09-03 14:12:39.955 W/System.err(19529): 	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:911)
09-03 14:12:39.955 W/System.err(19529): 	at android.view.Choreographer.doCallbacks(Choreographer.java:723)
09-03 14:12:39.955 W/System.err(19529): 	at android.view.Choreographer.doFrame(Choreographer.java:658)
09-03 14:12:39.955 W/System.err(19529): 	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:897)
09-03 14:12:39.955 W/System.err(19529): 	at android.os.Handler.handleCallback(Handler.java:790)
09-03 14:12:39.956 W/System.err(19529): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-03 14:12:39.956 W/System.err(19529): 	at android.os.Looper.loop(Looper.java:164)
09-03 14:12:39.956 W/System.err(19529): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-03 14:12:39.956 W/System.err(19529): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 14:12:39.956 W/System.err(19529): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-03 14:12:39.956 W/System.err(19529): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-03 14:12:39.956 W/System.err(19529): Caused by: java.lang.SecurityException: getImeiForSlot: Neither user 11139 nor current process has android.permission.READ_PHONE_STATE.
09-03 14:12:39.956 W/System.err(19529): 	at android.os.Parcel.readException(Parcel.java:2005)
09-03 14:12:39.956 W/System.err(19529): 	at android.os.Parcel.readException(Parcel.java:1951)
09-03 14:12:39.956 W/System.err(19529): 	at com.android.internal.telephony.ITelephony$Stub$Proxy.getImeiForSlot(ITelephony.java:4977)
09-03 14:12:39.956 W/System.err(19529): 	at android.telephony.TelephonyManager.getImei(TelephonyManager.java:1076)
09-03 14:12:39.956 W/System.err(19529): 	at android.telephony.TelephonyManager.getImei(TelephonyManager.java:1061)
09-03 14:12:39.956 W/System.err(19529): 	... 81 more
09-03 14:12:39.957 E/YLog    (19529): getIMEI??????0d80afaa50913110
09-03 14:12:39.958 W/bt_btm_ble( 2084): btm_ble_process_adv_pkt_cont device no longer discoverable, discarding advertising packet
09-03 14:12:40.264 W/bt_btm_ble( 2084): btm_ble_process_adv_pkt_cont device no longer discoverable, discarding advertising packet
09-03 14:12:40.278 W/bt_btm_ble( 2084): btm_ble_process_adv_pkt_cont device no longer discoverable, discarding advertising packet
09-03 14:12:40.283 W/bt_btm_ble( 2084): btm_ble_process_adv_pkt_cont device no longer discoverable, discarding advertising packet
09-03 14:12:40.314 W/System.err(19529): java.lang.reflect.InvocationTargetException
09-03 14:12:40.315 W/System.err(19529): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 14:12:40.315 W/System.err(19529): 	at com.linker.xlyt.Api.ad.ADApi.getIMEI(ADApi.java:134)
09-03 14:12:40.315 W/System.err(19529): 	at com.linker.xlyt.Api.ad.ADApi$1.addParams(ADApi.java:88)
09-03 14:12:40.315 W/System.err(19529): 	at com.hzlh.sdk.net.HttpMap.getMap(HttpMap.java:20)
09-03 14:12:40.315 W/System.err(19529): 	at com.linker.xlyt.Api.ad.ADApi.getAd(ADApi.java:80)
09-03 14:12:40.315 W/System.err(19529): 	at com.linker.xlyt.Api.ad.ADApi.getAd(ADApi.java:55)
09-03 14:12:40.315 W/System.err(19529): 	at com.linker.xlyt.module.newHome.ListenTVFragment.loadDate(ListenTVFragment.java:1098)
09-03 14:12:40.315 W/System.err(19529): 	at com.linker.xlyt.module.newHome.ListenTVFragment.init(ListenTVFragment.java:890)
09-03 14:12:40.315 W/System.err(19529): 	at com.linker.xlyt.module.play.fragment.BaseInitFragment.onStart(BaseInitFragment.java:65)
09-03 14:12:40.315 W/System.err(19529): 	at androidx.fragment.app.Fragment.performStart(Fragment.java:2730)
09-03 14:12:40.315 W/System.err(19529): 	at androidx.fragment.app.FragmentStateManager.start(FragmentStateManager.java:355)
09-03 14:12:40.315 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.moveToState(FragmentManager.java:1192)
09-03 14:12:40.315 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.performPendingDeferredStart(FragmentManager.java:1109)
09-03 14:12:40.315 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.startPendingDeferredFragments(FragmentManager.java:1517)
09-03 14:12:40.315 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.doPendingDeferredStart(FragmentManager.java:2285)
09-03 14:12:40.315 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.execSingleAction(FragmentManager.java:1823)
09-03 14:12:40.315 W/System.err(19529): 	at androidx.fragment.app.BackStackRecord.commitNowAllowingStateLoss(BackStackRecord.java:303)
09-03 14:12:40.315 W/System.err(19529): 	at androidx.fragment.app.FragmentStatePagerAdapter.finishUpdate(FragmentStatePagerAdapter.java:262)
09-03 14:12:40.316 W/System.err(19529): 	at androidx.viewpager.widget.ViewPager.populate(ViewPager.java:1244)
09-03 14:12:40.316 W/System.err(19529): 	at androidx.viewpager.widget.ViewPager.populate(ViewPager.java:1092)
09-03 14:12:40.316 W/System.err(19529): 	at androidx.viewpager.widget.ViewPager.onMeasure(ViewPager.java:1622)
09-03 14:12:40.316 W/System.err(19529): 	at com.linker.xlyt.view.InnerViewPager.onMeasure(InnerViewPager.java:110)
09-03 14:12:40.316 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.316 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:40.316 W/System.err(19529): 	at android.widget.LinearLayout.measureChildBeforeLayout(LinearLayout.java:1514)
09-03 14:12:40.316 W/System.err(19529): 	at android.widget.LinearLayout.measureVertical(LinearLayout.java:806)
09-03 14:12:40.316 W/System.err(19529): 	at android.widget.LinearLayout.onMeasure(LinearLayout.java:685)
09-03 14:12:40.316 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.316 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:40.316 W/System.err(19529): 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:185)
09-03 14:12:40.316 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.316 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:40.316 W/System.err(19529): 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:185)
09-03 14:12:40.316 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.316 W/System.err(19529): 	at android.widget.RelativeLayout.measureChildHorizontal(RelativeLayout.java:715)
09-03 14:12:40.316 W/System.err(19529): 	at android.widget.RelativeLayout.onMeasure(RelativeLayout.java:461)
09-03 14:12:40.316 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.316 W/System.err(19529): 	at android.widget.RelativeLayout.measureChildHorizontal(RelativeLayout.java:715)
09-03 14:12:40.316 W/System.err(19529): 	at android.widget.RelativeLayout.onMeasure(RelativeLayout.java:461)
09-03 14:12:40.316 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.316 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:40.316 W/System.err(19529): 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:185)
09-03 14:12:40.316 W/System.err(19529): 	at androidx.appcompat.widget.ContentFrameLayout.onMeasure(ContentFrameLayout.java:146)
09-03 14:12:40.316 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.316 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:40.316 W/System.err(19529): 	at android.widget.LinearLayout.measureChildBeforeLayout(LinearLayout.java:1514)
09-03 14:12:40.316 W/System.err(19529): 	at android.widget.LinearLayout.measureVertical(LinearLayout.java:806)
09-03 14:12:40.316 W/System.err(19529): 	at android.widget.LinearLayout.onMeasure(LinearLayout.java:685)
09-03 14:12:40.316 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.316 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:40.316 W/System.err(19529): 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:185)
09-03 14:12:40.317 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.317 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:40.317 W/System.err(19529): 	at android.widget.LinearLayout.measureChildBeforeLayout(LinearLayout.java:1514)
09-03 14:12:40.317 W/System.err(19529): 	at android.widget.LinearLayout.measureVertical(LinearLayout.java:806)
09-03 14:12:40.317 W/System.err(19529): 	at android.widget.LinearLayout.onMeasure(LinearLayout.java:685)
09-03 14:12:40.317 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.317 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:40.317 W/System.err(19529): 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:185)
09-03 14:12:40.317 W/System.err(19529): 	at com.android.internal.policy.DecorView.onMeasure(DecorView.java:724)
09-03 14:12:40.317 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.317 W/System.err(19529): 	at android.view.ViewRootImpl.performMeasure(ViewRootImpl.java:2422)
09-03 14:12:40.317 W/System.err(19529): 	at android.view.ViewRootImpl.measureHierarchy(ViewRootImpl.java:1504)
09-03 14:12:40.317 W/System.err(19529): 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:1761)
09-03 14:12:40.317 W/System.err(19529): 	at android.view.ViewRootImpl.doTraversal(ViewRootImpl.java:1392)
09-03 14:12:40.317 W/System.err(19529): 	at android.view.ViewRootImpl$TraversalRunnable.run(ViewRootImpl.java:6752)
09-03 14:12:40.317 W/System.err(19529): 	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:911)
09-03 14:12:40.317 W/System.err(19529): 	at android.view.Choreographer.doCallbacks(Choreographer.java:723)
09-03 14:12:40.317 W/System.err(19529): 	at android.view.Choreographer.doFrame(Choreographer.java:658)
09-03 14:12:40.317 W/System.err(19529): 	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:897)
09-03 14:12:40.317 W/System.err(19529): 	at android.os.Handler.handleCallback(Handler.java:790)
09-03 14:12:40.317 W/System.err(19529): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-03 14:12:40.317 W/System.err(19529): 	at android.os.Looper.loop(Looper.java:164)
09-03 14:12:40.317 W/System.err(19529): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-03 14:12:40.317 W/System.err(19529): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 14:12:40.317 W/System.err(19529): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-03 14:12:40.317 W/System.err(19529): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-03 14:12:40.318 W/System.err(19529): Caused by: java.lang.SecurityException: getImeiForSlot: Neither user 11139 nor current process has android.permission.READ_PHONE_STATE.
09-03 14:12:40.318 W/System.err(19529): 	at android.os.Parcel.readException(Parcel.java:2005)
09-03 14:12:40.318 W/System.err(19529): 	at android.os.Parcel.readException(Parcel.java:1951)
09-03 14:12:40.318 W/System.err(19529): 	at com.android.internal.telephony.ITelephony$Stub$Proxy.getImeiForSlot(ITelephony.java:4977)
09-03 14:12:40.318 W/System.err(19529): 	at android.telephony.TelephonyManager.getImei(TelephonyManager.java:1076)
09-03 14:12:40.318 W/System.err(19529): 	at android.telephony.TelephonyManager.getImei(TelephonyManager.java:1061)
09-03 14:12:40.318 W/System.err(19529): 	... 77 more
09-03 14:12:40.318 E/YLog    (19529): getIMEI??????0d80afaa50913110
09-03 14:12:40.332 W/System.err(19529): java.lang.reflect.InvocationTargetException
09-03 14:12:40.333 W/System.err(19529): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 14:12:40.333 W/System.err(19529): 	at com.linker.xlyt.Api.ad.ADApi.getIMEI(ADApi.java:134)
09-03 14:12:40.333 W/System.err(19529): 	at com.linker.xlyt.Api.ad.ADApi$1.addParams(ADApi.java:88)
09-03 14:12:40.333 W/System.err(19529): 	at com.hzlh.sdk.net.HttpMap.getMap(HttpMap.java:20)
09-03 14:12:40.333 W/System.err(19529): 	at com.linker.xlyt.Api.ad.ADApi.getAd(ADApi.java:80)
09-03 14:12:40.333 W/System.err(19529): 	at com.linker.xlyt.Api.ad.ADApi.getAd(ADApi.java:55)
09-03 14:12:40.333 W/System.err(19529): 	at com.linker.xlyt.module.newHome.ListenTVFragment.loadDate(ListenTVFragment.java:1098)
09-03 14:12:40.333 W/System.err(19529): 	at com.linker.xlyt.module.newHome.ListenTVFragment.init(ListenTVFragment.java:890)
09-03 14:12:40.333 W/System.err(19529): 	at com.linker.xlyt.module.play.fragment.BaseInitFragment.onStart(BaseInitFragment.java:65)
09-03 14:12:40.333 W/System.err(19529): 	at androidx.fragment.app.Fragment.performStart(Fragment.java:2730)
09-03 14:12:40.333 W/System.err(19529): 	at androidx.fragment.app.FragmentStateManager.start(FragmentStateManager.java:355)
09-03 14:12:40.333 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.moveToState(FragmentManager.java:1192)
09-03 14:12:40.333 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.performPendingDeferredStart(FragmentManager.java:1109)
09-03 14:12:40.333 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.startPendingDeferredFragments(FragmentManager.java:1517)
09-03 14:12:40.333 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.doPendingDeferredStart(FragmentManager.java:2285)
09-03 14:12:40.333 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.execSingleAction(FragmentManager.java:1823)
09-03 14:12:40.333 W/System.err(19529): 	at androidx.fragment.app.BackStackRecord.commitNowAllowingStateLoss(BackStackRecord.java:303)
09-03 14:12:40.333 W/System.err(19529): 	at androidx.fragment.app.FragmentStatePagerAdapter.finishUpdate(FragmentStatePagerAdapter.java:262)
09-03 14:12:40.333 W/System.err(19529): 	at androidx.viewpager.widget.ViewPager.populate(ViewPager.java:1244)
09-03 14:12:40.333 W/System.err(19529): 	at androidx.viewpager.widget.ViewPager.populate(ViewPager.java:1092)
09-03 14:12:40.334 W/System.err(19529): 	at androidx.viewpager.widget.ViewPager.onMeasure(ViewPager.java:1622)
09-03 14:12:40.334 W/System.err(19529): 	at com.linker.xlyt.view.InnerViewPager.onMeasure(InnerViewPager.java:110)
09-03 14:12:40.334 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.334 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:40.334 W/System.err(19529): 	at android.widget.LinearLayout.measureChildBeforeLayout(LinearLayout.java:1514)
09-03 14:12:40.334 W/System.err(19529): 	at android.widget.LinearLayout.measureVertical(LinearLayout.java:806)
09-03 14:12:40.334 W/System.err(19529): 	at android.widget.LinearLayout.onMeasure(LinearLayout.java:685)
09-03 14:12:40.334 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.334 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:40.334 W/System.err(19529): 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:185)
09-03 14:12:40.334 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.334 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:40.334 W/System.err(19529): 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:185)
09-03 14:12:40.334 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.334 W/System.err(19529): 	at android.widget.RelativeLayout.measureChildHorizontal(RelativeLayout.java:715)
09-03 14:12:40.334 W/System.err(19529): 	at android.widget.RelativeLayout.onMeasure(RelativeLayout.java:461)
09-03 14:12:40.334 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.334 W/System.err(19529): 	at android.widget.RelativeLayout.measureChildHorizontal(RelativeLayout.java:715)
09-03 14:12:40.334 W/System.err(19529): 	at android.widget.RelativeLayout.onMeasure(RelativeLayout.java:461)
09-03 14:12:40.334 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.334 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:40.334 W/System.err(19529): 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:185)
09-03 14:12:40.334 W/System.err(19529): 	at androidx.appcompat.widget.ContentFrameLayout.onMeasure(ContentFrameLayout.java:146)
09-03 14:12:40.334 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.334 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:40.334 W/System.err(19529): 	at android.widget.LinearLayout.measureChildBeforeLayout(LinearLayout.java:1514)
09-03 14:12:40.334 W/System.err(19529): 	at android.widget.LinearLayout.measureVertical(LinearLayout.java:806)
09-03 14:12:40.334 W/System.err(19529): 	at android.widget.LinearLayout.onMeasure(LinearLayout.java:685)
09-03 14:12:40.334 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.334 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:40.335 W/System.err(19529): 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:185)
09-03 14:12:40.335 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.335 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:40.335 W/System.err(19529): 	at android.widget.LinearLayout.measureChildBeforeLayout(LinearLayout.java:1514)
09-03 14:12:40.335 W/System.err(19529): 	at android.widget.LinearLayout.measureVertical(LinearLayout.java:806)
09-03 14:12:40.335 W/System.err(19529): 	at android.widget.LinearLayout.onMeasure(LinearLayout.java:685)
09-03 14:12:40.335 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.335 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:40.335 W/System.err(19529): 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:185)
09-03 14:12:40.335 W/System.err(19529): 	at com.android.internal.policy.DecorView.onMeasure(DecorView.java:724)
09-03 14:12:40.335 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.335 W/System.err(19529): 	at android.view.ViewRootImpl.performMeasure(ViewRootImpl.java:2422)
09-03 14:12:40.335 W/System.err(19529): 	at android.view.ViewRootImpl.measureHierarchy(ViewRootImpl.java:1504)
09-03 14:12:40.335 W/System.err(19529): 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:1761)
09-03 14:12:40.335 W/System.err(19529): 	at android.view.ViewRootImpl.doTraversal(ViewRootImpl.java:1392)
09-03 14:12:40.335 W/System.err(19529): 	at android.view.ViewRootImpl$TraversalRunnable.run(ViewRootImpl.java:6752)
09-03 14:12:40.335 W/System.err(19529): 	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:911)
09-03 14:12:40.335 W/System.err(19529): 	at android.view.Choreographer.doCallbacks(Choreographer.java:723)
09-03 14:12:40.335 W/System.err(19529): 	at android.view.Choreographer.doFrame(Choreographer.java:658)
09-03 14:12:40.335 W/System.err(19529): 	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:897)
09-03 14:12:40.335 W/System.err(19529): 	at android.os.Handler.handleCallback(Handler.java:790)
09-03 14:12:40.335 W/System.err(19529): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-03 14:12:40.335 W/System.err(19529): 	at android.os.Looper.loop(Looper.java:164)
09-03 14:12:40.335 W/System.err(19529): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-03 14:12:40.335 W/System.err(19529): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 14:12:40.335 W/System.err(19529): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-03 14:12:40.335 W/System.err(19529): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-03 14:12:40.336 W/System.err(19529): Caused by: java.lang.SecurityException: getImeiForSlot: Neither user 11139 nor current process has android.permission.READ_PHONE_STATE.
09-03 14:12:40.336 W/System.err(19529): 	at android.os.Parcel.readException(Parcel.java:2005)
09-03 14:12:40.336 W/System.err(19529): 	at android.os.Parcel.readException(Parcel.java:1951)
09-03 14:12:40.336 W/System.err(19529): 	at com.android.internal.telephony.ITelephony$Stub$Proxy.getImeiForSlot(ITelephony.java:4977)
09-03 14:12:40.336 W/System.err(19529): 	at android.telephony.TelephonyManager.getImei(TelephonyManager.java:1076)
09-03 14:12:40.336 W/System.err(19529): 	at android.telephony.TelephonyManager.getImei(TelephonyManager.java:1061)
09-03 14:12:40.336 W/System.err(19529): 	... 77 more
09-03 14:12:40.336 E/YLog    (19529): getIMEI??????0d80afaa50913110
09-03 14:12:40.349 W/System.err(19529): java.lang.reflect.InvocationTargetException
09-03 14:12:40.350 W/System.err(19529): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 14:12:40.350 W/System.err(19529): 	at com.linker.xlyt.Api.ad.ADApi.getIMEI(ADApi.java:134)
09-03 14:12:40.350 W/System.err(19529): 	at com.linker.xlyt.Api.ad.ADApi$1.addParams(ADApi.java:88)
09-03 14:12:40.350 W/System.err(19529): 	at com.hzlh.sdk.net.HttpMap.getMap(HttpMap.java:20)
09-03 14:12:40.350 W/System.err(19529): 	at com.linker.xlyt.Api.ad.ADApi.getAd(ADApi.java:80)
09-03 14:12:40.350 W/System.err(19529): 	at com.linker.xlyt.Api.ad.ADApi.getAd(ADApi.java:55)
09-03 14:12:40.350 W/System.err(19529): 	at com.linker.xlyt.module.newHome.ListenTVFragment.loadDate(ListenTVFragment.java:1098)
09-03 14:12:40.350 W/System.err(19529): 	at com.linker.xlyt.module.newHome.ListenTVFragment.init(ListenTVFragment.java:890)
09-03 14:12:40.350 W/System.err(19529): 	at com.linker.xlyt.module.play.fragment.BaseInitFragment.onStart(BaseInitFragment.java:65)
09-03 14:12:40.350 W/System.err(19529): 	at androidx.fragment.app.Fragment.performStart(Fragment.java:2730)
09-03 14:12:40.350 W/System.err(19529): 	at androidx.fragment.app.FragmentStateManager.start(FragmentStateManager.java:355)
09-03 14:12:40.350 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.moveToState(FragmentManager.java:1192)
09-03 14:12:40.350 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.performPendingDeferredStart(FragmentManager.java:1109)
09-03 14:12:40.350 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.startPendingDeferredFragments(FragmentManager.java:1517)
09-03 14:12:40.350 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.doPendingDeferredStart(FragmentManager.java:2285)
09-03 14:12:40.350 W/System.err(19529): 	at androidx.fragment.app.FragmentManager.execSingleAction(FragmentManager.java:1823)
09-03 14:12:40.350 W/System.err(19529): 	at androidx.fragment.app.BackStackRecord.commitNowAllowingStateLoss(BackStackRecord.java:303)
09-03 14:12:40.350 W/System.err(19529): 	at androidx.fragment.app.FragmentStatePagerAdapter.finishUpdate(FragmentStatePagerAdapter.java:262)
09-03 14:12:40.350 W/System.err(19529): 	at androidx.viewpager.widget.ViewPager.populate(ViewPager.java:1244)
09-03 14:12:40.350 W/System.err(19529): 	at androidx.viewpager.widget.ViewPager.populate(ViewPager.java:1092)
09-03 14:12:40.350 W/System.err(19529): 	at androidx.viewpager.widget.ViewPager.onMeasure(ViewPager.java:1622)
09-03 14:12:40.350 W/System.err(19529): 	at com.linker.xlyt.view.InnerViewPager.onMeasure(InnerViewPager.java:110)
09-03 14:12:40.350 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.350 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:40.351 W/System.err(19529): 	at android.widget.LinearLayout.measureChildBeforeLayout(LinearLayout.java:1514)
09-03 14:12:40.351 W/System.err(19529): 	at android.widget.LinearLayout.measureVertical(LinearLayout.java:806)
09-03 14:12:40.351 W/System.err(19529): 	at android.widget.LinearLayout.onMeasure(LinearLayout.java:685)
09-03 14:12:40.351 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.351 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:40.351 W/System.err(19529): 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:185)
09-03 14:12:40.351 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.351 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:40.351 W/System.err(19529): 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:185)
09-03 14:12:40.351 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.351 W/System.err(19529): 	at android.widget.RelativeLayout.measureChildHorizontal(RelativeLayout.java:715)
09-03 14:12:40.351 W/System.err(19529): 	at android.widget.RelativeLayout.onMeasure(RelativeLayout.java:461)
09-03 14:12:40.351 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.351 W/System.err(19529): 	at android.widget.RelativeLayout.measureChildHorizontal(RelativeLayout.java:715)
09-03 14:12:40.351 W/System.err(19529): 	at android.widget.RelativeLayout.onMeasure(RelativeLayout.java:461)
09-03 14:12:40.351 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.351 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:40.351 W/System.err(19529): 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:185)
09-03 14:12:40.351 W/System.err(19529): 	at androidx.appcompat.widget.ContentFrameLayout.onMeasure(ContentFrameLayout.java:146)
09-03 14:12:40.351 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.351 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:40.351 W/System.err(19529): 	at android.widget.LinearLayout.measureChildBeforeLayout(LinearLayout.java:1514)
09-03 14:12:40.351 W/System.err(19529): 	at android.widget.LinearLayout.measureVertical(LinearLayout.java:806)
09-03 14:12:40.351 W/System.err(19529): 	at android.widget.LinearLayout.onMeasure(LinearLayout.java:685)
09-03 14:12:40.351 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.351 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:40.351 W/System.err(19529): 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:185)
09-03 14:12:40.351 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.351 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:40.351 W/System.err(19529): 	at android.widget.LinearLayout.measureChildBeforeLayout(LinearLayout.java:1514)
09-03 14:12:40.351 W/System.err(19529): 	at android.widget.LinearLayout.measureVertical(LinearLayout.java:806)
09-03 14:12:40.351 W/System.err(19529): 	at android.widget.LinearLayout.onMeasure(LinearLayout.java:685)
09-03 14:12:40.351 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.351 W/System.err(19529): 	at android.view.ViewGroup.measureChildWithMargins(ViewGroup.java:6602)
09-03 14:12:40.351 W/System.err(19529): 	at android.widget.FrameLayout.onMeasure(FrameLayout.java:185)
09-03 14:12:40.351 W/System.err(19529): 	at com.android.internal.policy.DecorView.onMeasure(DecorView.java:724)
09-03 14:12:40.351 W/System.err(19529): 	at android.view.View.measure(View.java:22071)
09-03 14:12:40.351 W/System.err(19529): 	at android.view.ViewRootImpl.performMeasure(ViewRootImpl.java:2422)
09-03 14:12:40.352 W/System.err(19529): 	at android.view.ViewRootImpl.measureHierarchy(ViewRootImpl.java:1504)
09-03 14:12:40.352 W/System.err(19529): 	at android.view.ViewRootImpl.performTraversals(ViewRootImpl.java:1761)
09-03 14:12:40.352 W/System.err(19529): 	at android.view.ViewRootImpl.doTraversal(ViewRootImpl.java:1392)
09-03 14:12:40.352 W/System.err(19529): 	at android.view.ViewRootImpl$TraversalRunnable.run(ViewRootImpl.java:6752)
09-03 14:12:40.352 W/System.err(19529): 	at android.view.Choreographer$CallbackRecord.run(Choreographer.java:911)
09-03 14:12:40.352 W/System.err(19529): 	at android.view.Choreographer.doCallbacks(Choreographer.java:723)
09-03 14:12:40.352 W/System.err(19529): 	at android.view.Choreographer.doFrame(Choreographer.java:658)
09-03 14:12:40.352 W/System.err(19529): 	at android.view.Choreographer$FrameDisplayEventReceiver.run(Choreographer.java:897)
09-03 14:12:40.352 W/System.err(19529): 	at android.os.Handler.handleCallback(Handler.java:790)
09-03 14:12:40.352 W/System.err(19529): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-03 14:12:40.352 W/System.err(19529): 	at android.os.Looper.loop(Looper.java:164)
09-03 14:12:40.352 W/System.err(19529): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-03 14:12:40.352 W/System.err(19529): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 14:12:40.352 W/System.err(19529): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-03 14:12:40.352 W/System.err(19529): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-03 14:12:40.352 W/System.err(19529): Caused by: java.lang.SecurityException: getImeiForSlot: Neither user 11139 nor current process has android.permission.READ_PHONE_STATE.
09-03 14:12:40.352 W/System.err(19529): 	at android.os.Parcel.readException(Parcel.java:2005)
09-03 14:12:40.352 W/System.err(19529): 	at android.os.Parcel.readException(Parcel.java:1951)
09-03 14:12:40.352 W/System.err(19529): 	at com.android.internal.telephony.ITelephony$Stub$Proxy.getImeiForSlot(ITelephony.java:4977)
09-03 14:12:40.352 W/System.err(19529): 	at android.telephony.TelephonyManager.getImei(TelephonyManager.java:1076)
09-03 14:12:40.352 W/System.err(19529): 	at android.telephony.TelephonyManager.getImei(TelephonyManager.java:1061)
09-03 14:12:40.352 W/System.err(19529): 	... 77 more
09-03 14:12:40.352 E/YLog    (19529): getIMEI??????0d80afaa50913110
09-03 14:12:40.588 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:40.588 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:40.612 W/bt_btm_ble( 2084): btm_ble_process_adv_pkt_cont device no longer discoverable, discarding advertising packet
09-03 14:12:41.610 W/Adreno-EGL(19529): <qeglDrvAPI_eglGetConfigAttrib:607>: EGL_BAD_ATTRIBUTE
09-03 14:12:42.092 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:42.092 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:42.618 W/Native-LiteAV(19529): load library txffmpeg from system path 
09-03 14:12:42.621 W/Native-LiteAV(19529): load library txffmpeg true
09-03 14:12:42.621 W/Native-LiteAV(19529): load library traeimp-rtmp from system path 
09-03 14:12:42.622 W/Native-LiteAV(19529): load library traeimp-rtmp true
09-03 14:12:42.622 W/Native-LiteAV(19529): load library liteavsdk from system path 
09-03 14:12:42.634 W/JNI_UTIL(19529): JniHelper::setJavaVM(0xa3a99140), thread = -1488993116
09-03 14:12:42.635 W/Native-LiteAV(19529): load library liteavsdk true
09-03 14:12:42.638 W/Unknow  (19529): ^^^^^^^^^^Jan 15 2021^^^16:22:54^^^^^^^^^^[19529,19529][2021-09-03 +0800 14:12:42]
09-03 14:12:42.638 W/Unknow  (19529): del time out files time: 1
09-03 14:12:42.638 W/Unknow  (19529): get mmap time: 1
09-03 14:12:42.638 W/Unknow  (19529): SDK_VERSION: 8.3.9875
09-03 14:12:42.638 W/Unknow  (19529): SDK_ID: 1
09-03 14:12:42.638 W/Unknow  (19529): log appender mode:0, use mmap:1
09-03 14:12:43.202 E/cccccc  (19529): -------------12815658=========1
09-03 14:12:43.409 W/Glide   (19529): Load failed for null with size [0x0]
09-03 14:12:43.409 W/Glide   (19529): class com.bumptech.glide.load.engine.GlideException: Received null model
09-03 14:12:43.588 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:43.588 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:43.672 W/bt_btm_ble( 2084): btm_ble_process_adv_pkt_cont device no longer discoverable, discarding advertising packet
09-03 14:12:43.683 W/bt_btm_ble( 2084): btm_ble_process_adv_pkt_cont device no longer discoverable, discarding advertising packet
09-03 14:12:45.113 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:45.113 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:46.592 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:46.592 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:48.118 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:48.118 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:48.767 W/bt_btm_ble( 2084): btm_ble_process_adv_pkt_cont device no longer discoverable, discarding advertising packet
09-03 14:12:49.617 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:49.618 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:51.117 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:51.117 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:51.265 E/bt_btm  ( 2084): btm_flt_update_cb: bad length: 1
09-03 14:12:51.267 W/Settings( 9430): Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-03 14:12:51.272 E/bt_btm  ( 2084): btm_flt_update_cb: bad length: 1
09-03 14:12:51.282 W/Settings( 9430): Setting bluetooth_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-03 14:12:51.284 W/Settings( 9430): Setting wifi_on has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
09-03 14:12:52.622 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:52.622 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:54.089 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:54.090 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:55.634 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:55.634 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:57.101 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:57.102 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:58.598 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:12:58.598 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:00.090 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:00.090 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:01.051 E/AdaptScreenUtils(19529): getMetricsFromField: java.lang.ClassCastException: java.lang.Object cannot be cast to android.util.DisplayMetrics
09-03 14:13:01.051 E/AdaptScreenUtils(19529): getMetricsFromField: java.lang.ClassCastException: java.lang.Object cannot be cast to android.util.DisplayMetrics
09-03 14:13:01.098 E/okhttp  (19529): intercept: ==
09-03 14:13:01.134 W/Adreno-EGL(19529): <qeglDrvAPI_eglGetConfigAttrib:607>: EGL_BAD_ATTRIBUTE
09-03 14:13:01.592 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:01.592 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:02.003 E/okhttp  (19529): intercept: ==gradeId=882333480308965376&pageNum=1&pageSize=20&semester=882334209404829696&subjectId=882596660629209088&timestamp=1630649582002&key=8a19987413e82c496fab1d3f4a723969
09-03 14:13:02.037 W/Adreno-EGL(19529): <qeglDrvAPI_eglGetConfigAttrib:607>: EGL_BAD_ATTRIBUTE
09-03 14:13:02.970 W/Adreno-EGL(19529): <qeglDrvAPI_eglGetConfigAttrib:607>: EGL_BAD_ATTRIBUTE
09-03 14:13:03.102 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:03.102 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:04.597 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:04.597 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:05.594 W/BroadcastQueue(  620): Background execution not allowed: receiving Intent { act=com.tencent.assistant.st.report.PluginLogProcessorReceiver.TIME flg=0x14 (has extras) } to com.tencent.android.qqdownloader/com.tencent.assistant.st.report.PluginLogProcessorReceiver
09-03 14:13:05.667 W/InputEventReceiver(19529): Attempted to finish an input event but the input event receiver has already been disposed.
09-03 14:13:05.667 W/ViewRootImpl[PopupWindow:3fd5ccb](19529): Dropping event due to root view being removed: MotionEvent { action=ACTION_MOVE, actionButton=0, id[0]=0, x[0]=812.2479, y[0]=-62.020752, toolType[0]=TOOL_TYPE_FINGER, buttonState=0, metaState=0, flags=0x0, edgeFlags=0x0, pointerCount=1, historySize=0, eventTime=240107577, downTime=240107549, deviceId=5, source=0x1002 }
09-03 14:13:05.667 W/InputEventReceiver(19529): Attempted to finish an input event but the input event receiver has already been disposed.
09-03 14:13:06.097 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:06.097 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:06.420 E/AndroidRuntime(19529): FATAL EXCEPTION: main
09-03 14:13:06.420 E/AndroidRuntime(19529): Process: com.shinyv.cnr, PID: 19529
09-03 14:13:06.420 E/AndroidRuntime(19529): java.lang.IndexOutOfBoundsException: Inconsistency detected. Invalid item position 2(offset:2).state:8 androidx.recyclerview.widget.RecyclerView{a15f5c6 VFED..... ........ 0,0-1080,1578 #7f0907f4 app:id/recycler}, adapter:com.linker.xlyt.read.adapter.TextListAdapter@7f52e13, layout:androidx.recyclerview.widget.LinearLayoutManager@d209850, context:com.linker.xlyt.read.ui.activity.home.TextListActivity@36794
09-03 14:13:06.420 E/AndroidRuntime(19529): 	at androidx.recyclerview.widget.RecyclerView$Recycler.tryGetViewHolderForPositionByDeadline(RecyclerView.java:6183)
09-03 14:13:06.420 E/AndroidRuntime(19529): 	at androidx.recyclerview.widget.GapWorker.prefetchPositionWithDeadline(GapWorker.java:288)
09-03 14:13:06.420 E/AndroidRuntime(19529): 	at androidx.recyclerview.widget.GapWorker.flushTaskWithDeadline(GapWorker.java:345)
09-03 14:13:06.420 E/AndroidRuntime(19529): 	at androidx.recyclerview.widget.GapWorker.flushTasksWithDeadline(GapWorker.java:361)
09-03 14:13:06.420 E/AndroidRuntime(19529): 	at androidx.recyclerview.widget.GapWorker.prefetch(GapWorker.java:368)
09-03 14:13:06.420 E/AndroidRuntime(19529): 	at androidx.recyclerview.widget.GapWorker.run(GapWorker.java:399)
09-03 14:13:06.420 E/AndroidRuntime(19529): 	at android.os.Handler.handleCallback(Handler.java:790)
09-03 14:13:06.420 E/AndroidRuntime(19529): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-03 14:13:06.420 E/AndroidRuntime(19529): 	at android.os.Looper.loop(Looper.java:164)
09-03 14:13:06.420 E/AndroidRuntime(19529): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-03 14:13:06.420 E/AndroidRuntime(19529): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 14:13:06.420 E/AndroidRuntime(19529): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-03 14:13:06.420 E/AndroidRuntime(19529): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-03 14:13:06.420 E/CrashHandler(19529): In thread: Thread[main,5,main]
09-03 14:13:06.420 E/CrashHandler(19529): UncaughtException detected: java.lang.IndexOutOfBoundsException: Inconsistency detected. Invalid item position 2(offset:2).state:8 androidx.recyclerview.widget.RecyclerView{a15f5c6 VFED..... ........ 0,0-1080,1578 #7f0907f4 app:id/recycler}, adapter:com.linker.xlyt.read.adapter.TextListAdapter@7f52e13, layout:androidx.recyclerview.widget.LinearLayoutManager@d209850, context:com.linker.xlyt.read.ui.activity.home.TextListActivity@36794
09-03 14:13:06.420 E/CrashHandler(19529): 	at androidx.recyclerview.widget.RecyclerView$Recycler.tryGetViewHolderForPositionByDeadline(RecyclerView.java:6183)
09-03 14:13:06.420 E/CrashHandler(19529): 	at androidx.recyclerview.widget.GapWorker.prefetchPositionWithDeadline(GapWorker.java:288)
09-03 14:13:06.420 E/CrashHandler(19529): 	at androidx.recyclerview.widget.GapWorker.flushTaskWithDeadline(GapWorker.java:345)
09-03 14:13:06.420 E/CrashHandler(19529): 	at androidx.recyclerview.widget.GapWorker.flushTasksWithDeadline(GapWorker.java:361)
09-03 14:13:06.420 E/CrashHandler(19529): 	at androidx.recyclerview.widget.GapWorker.prefetch(GapWorker.java:368)
09-03 14:13:06.420 E/CrashHandler(19529): 	at androidx.recyclerview.widget.GapWorker.run(GapWorker.java:399)
09-03 14:13:06.420 E/CrashHandler(19529): 	at android.os.Handler.handleCallback(Handler.java:790)
09-03 14:13:06.420 E/CrashHandler(19529): 	at android.os.Handler.dispatchMessage(Handler.java:99)
09-03 14:13:06.420 E/CrashHandler(19529): 	at android.os.Looper.loop(Looper.java:164)
09-03 14:13:06.420 E/CrashHandler(19529): 	at android.app.ActivityThread.main(ActivityThread.java:6494)
09-03 14:13:06.420 E/CrashHandler(19529): 	at java.lang.reflect.Method.invoke(Native Method)
09-03 14:13:06.420 E/CrashHandler(19529): 	at com.android.internal.os.RuntimeInit$MethodAndArgsCaller.run(RuntimeInit.java:440)
09-03 14:13:06.420 E/CrashHandler(19529): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:807)
09-03 14:13:06.501 E/CrashHandler(19529): error : java.lang.IndexOutOfBoundsException: Inconsistency detected. Invalid item position 2(offset:2).state:8 androidx.recyclerview.widget.RecyclerView{a15f5c6 VFED..... ........ 0,0-1080,1578 #7f0907f4 app:id/recycler}, adapter:com.linker.xlyt.read.adapter.TextListAdapter@7f52e13, layout:androidx.recyclerview.widget.LinearLayoutManager@d209850, context:com.linker.xlyt.read.ui.activity.home.TextListActivity@36794
09-03 14:13:06.583 W/Avrcp   ( 2084): playState object null, sending STOPPED
09-03 14:13:06.584 W/zygote  (  620): kill(-19529, 9) failed: No such process
09-03 14:13:06.585 W/ActivityManager(  620): Scheduling restart of crashed service com.shinyv.cnr/com.linker.xlyt.components.service.XlPlayerService in 1000ms
09-03 14:13:06.585 W/ActivityManager(  620): Scheduling restart of crashed service com.shinyv.cnr/com.linker.xlyt.components.service.PlayerService in 11000ms
09-03 14:13:06.585 W/ActivityManager(  620): Scheduling restart of crashed service com.shinyv.cnr/com.linker.xlyt.components.service.PushIntentService in 21000ms
09-03 14:13:06.586 W/ActivityManager(  620): Force removing ActivityRecord{a0b5485 u0 com.shinyv.cnr/com.linker.xlyt.read.ui.activity.home.TextListActivity t29265}: app died, no saved state
09-03 14:13:06.587 E/Avrcp   ( 2084): play status change 0???0 mPlayStatusChangedNT: 1
09-03 14:13:06.588 E/Avrcp   ( 2084): play status change 0???0 mPlayStatusChangedNT: 1
09-03 14:13:06.589 E/Avrcp   ( 2084): play status change 0???0 mPlayStatusChangedNT: 1
09-03 14:13:06.589 E/Avrcp   ( 2084): play status change 0???0 mPlayStatusChangedNT: 1
09-03 14:13:06.618 W/ActivityManager(  620): setHasOverlayUi called on unknown pid: 19529
09-03 14:13:06.627 W/zygote  (  620): kill(-19529, 9) failed: No such process
09-03 14:13:06.630 W/ActivityManager(  620): Unable to start service Intent { act=com.android.launcher3.WINDOW_OVERLAY dat=app://org.lineageos.trebuchet:10029?v=7&cv=9 pkg=com.google.android.googlequicksearchbox } U=0: not found
09-03 14:13:06.645 W/ActivityManager(  620): Scheduling restart of crashed service com.shinyv.cnr/com.netease.nimlib.service.NimService in 20939ms
09-03 14:13:06.653 W/Adreno-EGL( 3141): <qeglDrvAPI_eglGetConfigAttrib:607>: EGL_BAD_ATTRIBUTE
09-03 14:13:06.654 W/zygote  (  620): kill(-19569, 9) failed: No such process
09-03 14:13:07.188 W/OpenGLRenderer( 3141): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
09-03 14:13:07.188 W/OpenGLRenderer( 3141): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
09-03 14:13:07.599 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:07.599 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:07.678 E/NotificationService(  620): Suppressing notification from package by user request.
09-03 14:13:07.809 E/MLInitializerProvider(20273): MLInitializerProvider Done
09-03 14:13:08.012 E/YLog    (20273): NIMClient.getStatus() = UNLOGIN
09-03 14:13:08.055 W/ZIDThreadPoolEx(20388): type=1400 audit(0.0:13406): avc: denied { read } for name="boot_id" dev="proc" ino=3144719 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:proc:s0 tclass=file permissive=0
09-03 14:13:08.073 W/ResourceType(20273): No package identifier when getting value for resource number 0x00000000
09-03 14:13:08.074 W/System.err(20273): android.content.res.Resources$NotFoundException: String resource ID #0x0
09-03 14:13:08.074 W/System.err(20273): 	at android.content.res.Resources.getText(Resources.java:339)
09-03 14:13:08.075 W/System.err(20273): 	at android.content.res.Resources.getString(Resources.java:433)
09-03 14:13:08.075 W/System.err(20273): 	at com.umeng.umzid.ZIDManager.a(:21)
09-03 14:13:08.075 W/System.err(20273): 	at com.umeng.umzid.ZIDManager.b(:5)
09-03 14:13:08.076 W/System.err(20273): 	at com.umeng.umzid.ZIDManager$b.run(Unknown Source:4)
09-03 14:13:08.076 W/System.err(20273): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:457)
09-03 14:13:08.077 W/System.err(20273): 	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
09-03 14:13:08.077 W/System.err(20273): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:301)
09-03 14:13:08.077 W/System.err(20273): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1162)
09-03 14:13:08.077 W/System.err(20273): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:636)
09-03 14:13:08.078 W/System.err(20273): 	at java.lang.Thread.run(Thread.java:764)
09-03 14:13:08.139 E/EXTEcService(20273): Query command: 3000
09-03 14:13:08.140 E/EXTEcService(20273): Emergency configuration has not yet dispatched. Command: 3000 has been suspended
09-03 14:13:08.265 W/ZIDThreadPoolEx(20417): type=1400 audit(0.0:13407): avc: denied { read } for name="boot_id" dev="proc" ino=3144719 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:proc:s0 tclass=file permissive=0
09-03 14:13:08.301 W/ResourceType(20347): No package identifier when getting value for resource number 0x00000000
09-03 14:13:08.302 W/System.err(20347): android.content.res.Resources$NotFoundException: String resource ID #0x0
09-03 14:13:08.302 W/System.err(20347): 	at android.content.res.Resources.getText(Resources.java:339)
09-03 14:13:08.302 W/System.err(20347): 	at android.content.res.Resources.getString(Resources.java:433)
09-03 14:13:08.302 W/System.err(20347): 	at com.umeng.umzid.ZIDManager.a(:21)
09-03 14:13:08.302 W/System.err(20347): 	at com.umeng.umzid.ZIDManager.b(:5)
09-03 14:13:08.302 W/System.err(20347): 	at com.umeng.umzid.ZIDManager$b.run(Unknown Source:4)
09-03 14:13:08.302 W/System.err(20347): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:457)
09-03 14:13:08.302 W/System.err(20347): 	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
09-03 14:13:08.302 W/System.err(20347): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:301)
09-03 14:13:08.302 W/System.err(20347): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1162)
09-03 14:13:08.302 W/System.err(20347): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:636)
09-03 14:13:08.302 W/System.err(20347): 	at java.lang.Thread.run(Thread.java:764)
09-03 14:13:08.318 W/System.err(20273): java.lang.ClassNotFoundException: Didn't find class "com.tencent.common.manifest.DefaultLoader" on path: DexPathList[[zip file "/data/user/0/com.shinyv.cnr/app_tbs/core_share/tbs_jars_fusion_dex.jar"],nativeLibraryDirectories=[/data/user/0/com.shinyv.cnr/app_tbs/core_share, /data/user/0/com.shinyv.cnr/app_tbs/share/plugins/com.tencent.qb.plugin.videodecode, /system/lib, /system/vendor/lib]]
09-03 14:13:08.321 W/System.err(20273): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:125)
09-03 14:13:08.322 W/System.err(20273): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:379)
09-03 14:13:08.322 W/System.err(20273): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:312)
09-03 14:13:08.322 W/System.err(20273): 	at com.tencent.common.manifest.AppManifest.a(Unknown Source:10)
09-03 14:13:08.322 W/System.err(20273): 	at com.tencent.common.manifest.AppManifest.getInstance(Unknown Source:16)
09-03 14:13:08.322 W/System.err(20273): 	at com.tencent.basesupport.ModuleProxy.get(TbsJavaCore:66)
09-03 14:13:08.322 W/System.err(20273): 	at com.tencent.common.threadpool.BrowserExecutorSupplier$BackgroundRunable.run(TbsJavaCore:810)
09-03 14:13:08.322 W/System.err(20273): 	at com.tencent.common.threadpool.MyThreadPoolExecutor.a(TbsJavaCore:1093)
09-03 14:13:08.322 W/System.err(20273): 	at com.tencent.common.threadpool.MyThreadPoolExecutor$a.run(TbsJavaCore:581)
09-03 14:13:08.322 W/System.err(20273): 	at java.lang.Thread.run(Thread.java:764)
09-03 14:13:08.323 W/System.err(20273): 	at com.tencent.common.threadpool.QBThreadFactory$1.run(TbsJavaCore:48)
09-03 14:13:08.331 E/libc    (20273): Access denied finding property "net.dns1"
09-03 14:13:08.379 W/work_thread(20462): type=1400 audit(0.0:13408): avc: denied { read } for name="boot_id" dev="proc" ino=3144719 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:proc:s0 tclass=file permissive=0
09-03 14:13:08.392 W/ZIDThreadPoolEx(20468): type=1400 audit(0.0:13409): avc: denied { read } for name="boot_id" dev="proc" ino=3144719 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:proc:s0 tclass=file permissive=0
09-03 14:13:08.440 W/ResourceType(20273): No package identifier when getting value for resource number 0x00000000
09-03 14:13:08.441 W/System.err(20273): android.content.res.Resources$NotFoundException: String resource ID #0x0
09-03 14:13:08.442 W/System.err(20273): 	at android.content.res.Resources.getText(Resources.java:339)
09-03 14:13:08.442 W/System.err(20273): 	at android.content.res.Resources.getString(Resources.java:433)
09-03 14:13:08.442 W/System.err(20273): 	at com.umeng.umzid.ZIDManager.a(:21)
09-03 14:13:08.442 W/System.err(20273): 	at com.umeng.umzid.ZIDManager.b(:5)
09-03 14:13:08.442 W/System.err(20273): 	at com.umeng.umzid.ZIDManager$d.run(Unknown Source:4)
09-03 14:13:08.442 W/System.err(20273): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:457)
09-03 14:13:08.442 W/System.err(20273): 	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
09-03 14:13:08.442 W/System.err(20273): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:301)
09-03 14:13:08.442 W/System.err(20273): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1162)
09-03 14:13:08.442 W/System.err(20273): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:636)
09-03 14:13:08.442 W/System.err(20273): 	at java.lang.Thread.run(Thread.java:764)
09-03 14:13:08.488 E/EXTEcService(20273): Handle emergency commands in tbs extension, status: 1
09-03 14:13:08.488 E/EXTEcService(20273): Ignore all unhandled emergencies, status: 1, command size: 0
09-03 14:13:08.489 E/TBSEcService(20273): Handle emergency commands in tbs shell, status: 1
09-03 14:13:08.489 E/TBSEcService(20273): Ignore all unhandled emergencies, status: 1, command size: 0
09-03 14:13:08.521 W/FileUtils(20273): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:13:08.521 W/FileUtils(20273): Failed to chmod(/data/user/0/com.tencent.mm/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:13:08.527 E/libc    (20273): Access denied finding property "net.dns1"
09-03 14:13:08.541 W/FileUtils(20273): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:13:08.542 W/FileUtils(20273): Failed to chmod(/data/user/0/com.tencent.mobileqq/app_tbs_common_share): android.system.ErrnoException: chmod failed: EACCES (Permission denied)
09-03 14:13:08.570 W/System.err(20273): android.content.pm.PackageManager$NameNotFoundException: com.heytap.openid
09-03 14:13:08.570 W/System.err(20273): 	at android.app.ApplicationPackageManager.getPackageInfoAsUser(ApplicationPackageManager.java:173)
09-03 14:13:08.570 W/System.err(20273): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:144)
09-03 14:13:08.570 W/System.err(20273): 	at com.tencent.tbsqmsp.sdk.g.g.e.a(Unknown Source:8)
09-03 14:13:08.571 W/System.err(20273): 	at com.tencent.tbsqmsp.sdk.g.g.b.c(Unknown Source:6)
09-03 14:13:08.571 W/System.err(20273): 	at com.tencent.tbsqmsp.sdk.g.g.c.a(Unknown Source:4)
09-03 14:13:08.571 W/System.err(20273): 	at com.tencent.tbsqmsp.sdk.base.e.a(Unknown Source:117)
09-03 14:13:08.571 W/System.err(20273): 	at com.tencent.tbsqmsp.sdk.u.U.getOAID(Unknown Source:5)
09-03 14:13:08.571 W/System.err(20273): 	at com.tencent.tbsbeacon.a.c.f.O(TbsJavaCore:3)
09-03 14:13:08.571 W/System.err(20273): 	at com.tencent.tbsbeacon.a.c.f.<init>(TbsJavaCore:16)
09-03 14:13:08.571 W/System.err(20273): 	at com.tencent.tbsbeacon.a.c.f.<clinit>(TbsJavaCore:1)
09-03 14:13:08.571 W/System.err(20273): 	at com.tencent.tbsbeacon.a.c.f.p(Unknown Source:0)
09-03 14:13:08.571 W/System.err(20273): 	at com.tencent.tbsbeacon.a.e.b.a(TbsJavaCore:59)
09-03 14:13:08.571 W/System.err(20273): 	at com.tencent.tbsbeacon.e.g.a(TbsJavaCore:11)
09-03 14:13:08.571 W/System.err(20273): 	at com.tencent.tbsbeacon.e.e.run(TbsJavaCore:2)
09-03 14:13:08.571 W/System.err(20273): 	at com.tencent.tbsbeacon.a.b.e.run(TbsJavaCore:1)
09-03 14:13:08.571 W/System.err(20273): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:457)
09-03 14:13:08.571 W/System.err(20273): 	at java.util.concurrent.FutureTask.run(FutureTask.java:266)
09-03 14:13:08.571 W/System.err(20273): 	at java.util.concurrent.ScheduledThreadPoolExecutor$ScheduledFutureTask.run(ScheduledThreadPoolExecutor.java:301)
09-03 14:13:08.571 W/System.err(20273): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1162)
09-03 14:13:08.571 W/System.err(20273): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:636)
09-03 14:13:08.571 W/System.err(20273): 	at java.lang.Thread.run(Thread.java:764)
09-03 14:13:08.612 W/SSLCertificateSocketFactory(20347): Bypassing SSL security checks at caller's request
09-03 14:13:08.657 E/DatabaseUtils(  620): Writing exception to parcel
09-03 14:13:08.657 E/DatabaseUtils(  620): java.lang.SecurityException: com.shinyv.cnr was not granted  this permission: android.permission.WRITE_SETTINGS.
09-03 14:13:08.657 E/DatabaseUtils(  620): 	at android.provider.Settings.isCallingPackageAllowedToPerformAppOpsProtectedOperation(Settings.java:11325)
09-03 14:13:08.657 E/DatabaseUtils(  620): 	at android.provider.Settings.checkAndNoteWriteSettingsOperation(Settings.java:11207)
09-03 14:13:08.657 E/DatabaseUtils(  620): 	at com.android.providers.settings.SettingsProvider.mutateSystemSetting(SettingsProvider.java:1380)
09-03 14:13:08.657 E/DatabaseUtils(  620): 	at com.android.providers.settings.SettingsProvider.insertSystemSetting(SettingsProvider.java:1355)
09-03 14:13:08.657 E/DatabaseUtils(  620): 	at com.android.providers.settings.SettingsProvider.call(SettingsProvider.java:373)
09-03 14:13:08.657 E/DatabaseUtils(  620): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:401)
09-03 14:13:08.657 E/DatabaseUtils(  620): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:272)
09-03 14:13:08.657 E/DatabaseUtils(  620): 	at android.os.Binder.execTransact(Binder.java:697)
09-03 14:13:08.665 W/beacon-thread-1(20491): type=1400 audit(0.0:13410): avc: denied { read } for name="address" dev="sysfs" ino=23017 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:sysfs:s0 tclass=file permissive=0
09-03 14:13:08.674 W/Adreno-EGL(20273): <qeglDrvAPI_eglGetConfigAttrib:607>: EGL_BAD_ATTRIBUTE
09-03 14:13:08.702 E/TBSEcService(20273): Emergency configuration has been dispatched, status: 1. Command query: 2000 ignored
09-03 14:13:08.703 E/libc    (20273): Access denied finding property "net.dns1"
09-03 14:13:08.702 W/beacon-thread-1(20491): type=1400 audit(0.0:13411): avc: denied { read } for name="type" dev="sysfs" ino=18777 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:sysfs:s0 tclass=file permissive=0
09-03 14:13:08.712 W/beacon-thread-1(20491): type=1400 audit(0.0:13412): avc: denied { read } for name="name" dev="sysfs" ino=18770 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:sysfs:s0 tclass=file permissive=0
09-03 14:13:08.743 W/SSLCertificateSocketFactory(20347): Bypassing SSL security checks at caller's request
09-03 14:13:09.092 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:09.092 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:09.217 E/libc    (20273): Access denied finding property "net.dns1"
09-03 14:13:09.218 E/libc    (20273): Access denied finding property "net.dns1"
09-03 14:13:09.224 E/libc    (20273): Access denied finding property "net.dns1"
09-03 14:13:09.381 W/System.err(20273): java.io.FileNotFoundException: /data/user/0/com.shinyv.cnr/cache/optlist.ser (No such file or directory)
09-03 14:13:09.382 W/System.err(20273): 	at java.io.FileInputStream.open0(Native Method)
09-03 14:13:09.382 W/System.err(20273): 	at java.io.FileInputStream.open(FileInputStream.java:200)
09-03 14:13:09.382 W/System.err(20273): 	at java.io.FileInputStream.<init>(FileInputStream.java:150)
09-03 14:13:09.382 W/System.err(20273): 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
09-03 14:13:09.382 W/System.err(20273): 	at com.tencent.smtt.net.b.a(TbsJavaCore:60)
09-03 14:13:09.382 W/System.err(20273): 	at com.tencent.smtt.net.b.c(TbsJavaCore:170)
09-03 14:13:09.382 W/System.err(20273): 	at com.tencent.smtt.net.NetworkSmttService.preconnectMainResources(TbsJavaCore:151)
09-03 14:13:09.387 E/libc    (20273): Access denied finding property "net.dns1"
09-03 14:13:09.575 W/ActivityManager(  620): Unable to start service Intent { act=action.com.heytap.openid.OPEN_ID_SERVICE cmp=com.heytap.openid/.IdentifyService } U=0: not found
09-03 14:13:09.576 W/ActivityManager(  620): Unable to start service Intent { act=action.com.heytap.openid.OPEN_ID_SERVICE cmp=com.heytap.openid/.IdentifyService } U=0: not found
09-03 14:13:10.626 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:10.626 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:12.117 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:12.118 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:13.587 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:13.587 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:15.136 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:15.136 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:16.628 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:16.628 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:18.130 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????
09-03 14:13:18.130 E/WildToolbarNotification( 3253): processFlag: daemon, ???????????????????????????????????????