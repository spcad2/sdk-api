---
UID: NF:taskschd.IRepetitionPattern.get_Interval
title: IRepetitionPattern::get_Interval (taskschd.h)
description: Gets or sets the amount of time between each restart of the task.helpviewer_keywords: ["IRepetitionPattern interface [Task Scheduler]","Interval property","IRepetitionPattern.Interval","IRepetitionPattern.get_Interval","IRepetitionPattern::Interval","IRepetitionPattern::get_Interval","IRepetitionPattern::put_Interval","Interval property [Task Scheduler]","Interval property [Task Scheduler]","IRepetitionPattern interface","get_Interval","taskschd.irepetitionpattern_interval","taskschd/IRepetitionPattern::Interval","taskschd/IRepetitionPattern::get_Interval","taskschd/IRepetitionPattern::put_Interval"]
old-location: taskschd\irepetitionpattern_interval.htm
tech.root: taskschd
ms.assetid: 3ba8e4b8-c0f9-4b73-8351-b1c1b32a1e39
ms.date: 12/05/2018
ms.keywords: IRepetitionPattern interface [Task Scheduler],Interval property, IRepetitionPattern.Interval, IRepetitionPattern.get_Interval, IRepetitionPattern::Interval, IRepetitionPattern::get_Interval, IRepetitionPattern::put_Interval, Interval property [Task Scheduler], Interval property [Task Scheduler],IRepetitionPattern interface, get_Interval, taskschd.irepetitionpattern_interval, taskschd/IRepetitionPattern::Interval, taskschd/IRepetitionPattern::get_Interval, taskschd/IRepetitionPattern::put_Interval
f1_keywords:
- taskschd/IRepetitionPattern.Interval
dev_langs:
- c++
req.header: taskschd.h
req.include-header: 
req.target-type: Windows
req.target-min-winverclnt: Windows Vista [desktop apps only]
req.target-min-winversvr: Windows Server 2008 [desktop apps only]
req.kmdf-ver: 
req.umdf-ver: 
req.ddi-compliance: 
req.unicode-ansi: 
req.idl: 
req.max-support: 
req.namespace: 
req.assembly: 
req.type-library: 
req.lib: Taskschd.lib
req.dll: Taskschd.dll
req.irql: 
topic_type:
- APIRef
- kbSyntax
api_type:
- COM
api_location:
- taskschd.dll
api_name:
- IRepetitionPattern.Interval
- IRepetitionPattern.get_Interval
- IRepetitionPattern.put_Interval
targetos: Windows
req.typenames: 
req.redist: 
ms.custom: 19H1
---

# IRepetitionPattern::get_Interval


## -description


Gets or sets the amount of time between each restart of the task.

This property is read/write.


## -parameters


## -remarks



If you specify a repetition duration for a task, you must also specify the repetition interval.

When reading or writing XML for a task, the repetition interval is specified in the  <a href="https://docs.microsoft.com/windows/desktop/TaskSchd/taskschedulerschema-interval-repetitiontype-element">Interval</a> element of the Task Scheduler schema.




## -see-also




<a href="https://docs.microsoft.com/windows/desktop/api/taskschd/nn-taskschd-irepetitionpattern">IRepetitionPattern</a>



<a href="https://docs.microsoft.com/windows/desktop/TaskSchd/task-scheduler-start-page">Task Scheduler</a>
 

 

