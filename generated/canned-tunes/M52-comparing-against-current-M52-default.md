# M52-comparing-against-current-M52-default

// canned tune https://rusefi.com/online/view.php?msq=1591

```
    // default 0.0
    engineConfiguration->trigger.customTotalToothCount = 3;
    // default 0.0
    engineConfiguration->globalTriggerAngleOffset = 320;
    // default "Single Tooth"
    engineConfiguration->vvtMode[0] = VVT_INACTIVE;
    // default 40.0
    engineConfiguration->camDecoder2jzPrecision = 25;
    // default 450.0
    engineConfiguration->vvtOffsets[0] = 10;
    // default "false"
    engineConfiguration->overrideVvtTriggerGaps = true;
    // default 0.0
    engineConfiguration->gapVvtTrackingLengthOverride = 2;
    // default 0.0
    engineConfiguration->triggerVVTGapOverrideFrom[0] = 0.3;
    // default 0.0
    engineConfiguration->triggerVVTGapOverrideTo[0] = 0.6;
    // default 0.0
    engineConfiguration->triggerVVTGapOverrideFrom[1] = 2.1;
    // default 0.0
    engineConfiguration->triggerVVTGapOverrideTo[1] = 2.5;
    // default "false"
    engineConfiguration->verboseVVTDecoding = true;
    // default "false"
    engineConfiguration->verboseTriggerSynchDetails = true;
    // default 200.0
    engineConfiguration->injector.flow = 350;
    // default 300.0
    engineConfiguration->fuelReferencePressure = 100;
    // default 0.0
    engineConfiguration->cylinderBankSelect[0] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[1] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[2] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[3] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[4] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[5] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[6] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[7] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[8] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[9] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[10] = 1;
    // default 0.0
    engineConfiguration->cylinderBankSelect[11] = 1;
    // default 4.0
    engineConfiguration->benchTestOnTime = 5;
    // default "GPPWM Output 3"
    engineConfiguration->ignBlends[0].blendParameter = GPPWM_Zero;
    // default "Aux Linear 1"
    engineConfiguration->veBlends[2].blendParameter = GPPWM_Zero;
    // default "IAT"
    engineConfiguration->boostOpenLoopBlends[0].blendParameter = GPPWM_Zero;
    // default "Aux Temp 2"
    engineConfiguration->boostClosedLoopBlends[1].blendParameter = GPPWM_Zero;
    // default 0.0
    engineConfiguration->tpsMin = 120;
    // default 1000.0
    engineConfiguration->tpsMax = 791;
    // default "Normal"
    engineConfiguration->clutchDownPinInverted = false;
    // default "Normal"
    engineConfiguration->clutchUpPinInverted = false;
    // default 300.0
    engineConfiguration->idle.solenoidFrequency = 200;
    // default 3.0
    engineConfiguration->idleStepperReactionTime = 10;
    // default 200.0
    engineConfiguration->idleStepperTotalSteps = 150;
    // default 15.0
    engineConfiguration->etbIdleThrottleRange = 5;
    // default -20.0
    engineConfiguration->idleRpmPid.minValue = 0;
    // default 20.0
    engineConfiguration->idleRpmPid.maxValue = 99;
    // default 15.0
    engineConfiguration->acIdleExtraOffset = 0;
    // default 2.0
    engineConfiguration->fan1ExtraIdle = 0;
    // default 2.0
    engineConfiguration->fan2ExtraIdle = 0;
    // default 2.0
    engineConfiguration->iacByTpsTaper = 15;
    // default 5.0
    engineConfiguration->idlePidDeactivationTpsThreshold = 1;
    // default "false"
    engineConfiguration->useSeparateAdvanceForIdle = true;
    // default 0.0
    engineConfiguration->iacByTpsHoldTime = 1.5;
    // default 0.0
    engineConfiguration->iacByTpsDecayTime = 3.5;
    // default "false"
    engineConfiguration->useIdleTimingPidControl = true;
    // default 0.1
    engineConfiguration->idleTimingPid.pFactor = 0.09;
    // default 0.0
    engineConfiguration->idleTimingPid.dFactor = 5.0E-4;
    // default -10.0
    engineConfiguration->idleTimingPid.minValue = -5;
    // default 10.0
    engineConfiguration->idleTimingPid.maxValue = 5;
    // default 92.0
    engineConfiguration->fanOnTemperature = 95;
    // default 88.0
    engineConfiguration->fanOffTemperature = 91;
    // default "false"
    engineConfiguration->disableFan1WhenStopped = true;
    // default 0.5
    engineConfiguration->acDelay = 0;
    // default 4.0
    engineConfiguration->startUpFuelPumpDuration = 2;
    // default 20.0
    engineConfiguration->knockRetardAggression = 0;
    // default 3.0
    engineConfiguration->knockRetardReapplyRate = 0;
    // default 500.0
    engineConfiguration->vvtControlMinRpm = 800;
    // default "Speed Density"
    engineConfiguration->fuelAlgorithm = LM_ALPHA_N;
    // default "MAP"
    engineConfiguration->debugMode = DBG_22;
    // default "yes"
    engineConfiguration->cutFuelOnHardLimit = no;
    // default 7000.0
    engineConfiguration->rpmHardLimit = 10000;
    // default 300.0
    engineConfiguration->boostCutPressure = 0;
    // default 4.0
    engineConfiguration->rpmSoftLimitTimingRetard = 10;
    // default 250.0
    engineConfiguration->etbRevLimitRange = 0;
    // default "Simultaneous"
    engineConfiguration->crankingInjectionMode = IM_BATCH;
    // default "false"
    engineConfiguration->overrideCrankingIacSetting = true;
    // default 6.0
    engineConfiguration->crankingTimingAngle = 0;
    // default 0.5
    engineConfiguration->primingDelay = 0.7;
    // default "true"
    engineConfiguration->isCylinderCleanupEnabled = false;
    // default 550.0
    engineConfiguration->cranking.rpm = 400;
    // default 40.0
    engineConfiguration->tpsAccelEnrichmentThreshold = 200;
    // default 0.0
    engineConfiguration->tpsDecelEnleanmentThreshold = 7;
    // default 0.0
    engineConfiguration->tpsAccelFractionPeriod = 3;
    // default 1.0
    engineConfiguration->tpsAccelFractionDivisor = 0.3;
    // default 2000.0
    engineConfiguration->boostControlMinRpm = 0;
    // default 30.0
    engineConfiguration->boostControlMinTps = 0;
    // default 110.0
    engineConfiguration->boostControlMinMap = 0;
    // default "false"
    engineConfiguration->coastingFuelCutEnabled = true;
    // default 60.0
    engineConfiguration->coastingFuelCutClt = -10;
    // default 1500.0
    engineConfiguration->coastingFuelCutRpmHigh = 2600;
    // default 1300.0
    engineConfiguration->coastingFuelCutRpmLow = 2500;
    // default 30.0
    engineConfiguration->coastingFuelCutMap = 60;
    // default 0.0
    engineConfiguration->dfcoDelay = 2.5;
    // default 5.0
    engineConfiguration->acrRevolutions = 0;
    // default "true"
    engineConfiguration->watchOutForLinearTime = false;
    // default 250.0
    engineConfiguration->gppwm[3].pwmFrequency = 100;
    // default 3.0
    engineConfiguration->hpfpCamLobes = 0;
    // default 10.0
    engineConfiguration->hpfpPeakPos = 0;
    // default 0.29
    engineConfiguration->hpfpPumpVolume = 0;
    // default 10.0
    engineConfiguration->hpfpMinAngle = 0;
    // default 30.0
    engineConfiguration->hpfpActivationAngle = 0;
    // default 2000.0
    engineConfiguration->hpfpTargetDecay = 0;
    // default 0.01
    engineConfiguration->hpfpPidP = 0;
    // default 3.0E-4
    engineConfiguration->hpfpPidI = 0;


	cannedknockNoiseRpmBins();
	cannedknockBaseNoise();
	cannedsparkDwellRpmBins();
	cannedsparkDwellValues();
	canneddwellVoltageCorrVoltBins();
	canneddwellVoltageCorrValues();
	cannedtpsTspCorrValuesBins();
	cannedtpsTspCorrValues();
	cannedprimeBins();
	cannedprimeValues();
	cannedmap_samplingAngleBins();
	cannedmap_samplingAngle();
	cannedmap_samplingWindowBins();
	cannedmap_samplingWindow();
	cannedvrThreshold1_rpmBins();
	cannedvrThreshold2_rpmBins();
	cannedmafDecodingBins();
	cannedmafDecoding();
	cannediatFuelCorrBins();
	cannediatFuelCorr();
	cannedcltFuelCorrBins();
	cannedcltFuelCorr();
	cannedcrankingFuelBins();
	cannedcrankingFuelCoef();
	cannedcrankingFuelCoefE100();
	cannedcltRevLimitRpmBins();
	cannedcltRevLimitRpm();
	cannedcrankingCycleBins();
	cannedcrankingCycleCoef();
	cannedcltIdleCorrBins();
	cannedcltIdleCorr();
	cannedcltCrankingCorr();
	cannedcltIdleRpm();
	cannedidleAdvanceBins();
	cannedidleAdvance();
	cannedfuelLevelBins();
	cannedfuelLevelValues();
	cannedhpfpLobeProfileQuantityBins();
	cannedhpfpLobeProfileAngle();
	cannedhpfpDeadtimeVoltsBins();
	cannedwwCltBins();
	cannedwwTauCltValues();
	cannedwwMapBins();
	cannedwwTauMapValues();
	cannedwwBetaCltValues();
	cannedwwBetaMapValues();
	cannedtcu_tccTpsBins();
	cannedtcu_tccLockSpeed();
	cannedtcu_tccUnlockSpeed();
	cannedtcu_pcAirmassBins();
	cannedtcu_pcValsR();
	cannedtcu_pcValsN();
	cannedtcu_pcVals1();
	cannedtcu_pcVals2();
	cannedtcu_pcVals3();
	cannedtcu_pcVals4();
	cannedtcu_pcVals12();
	cannedtcu_pcVals23();
	cannedtcu_pcVals34();
	cannedtcu_pcVals21();
	cannedtcu_pcVals32();
	cannedtcu_pcVals43();
	cannedtcu_32SpeedBins();
	cannedtcu_32Vals();
	cannedtcu_rangeM();
	cannedtcu_rangeM3();
	cannedtcu_rangeM2();
	cannedtcu_rangeM1();
	cannedignBlends1_blendBins();
	cannedignBlends2_blendBins();
	cannedignBlends2_blendValues();
	cannedveBlends3_blendBins();
	cannedveBlends4_blendBins();
	cannedveBlends4_blendValues();
	cannedboostOpenLoopBlends1_blendBins();
	cannedboostClosedLoopBlends2_blendBins();
	cannedthrottleEstimateEffectiveAreaBins();
	cannedtpsTpsAccelFromRpmBins();
	cannedtpsTpsAccelToRpmBins();
	cannedtpsTpsAccelTable();
	cannedboostRpmBins();
	cannedboostTableOpenLoop();
	cannedvvtTable1RpmBins();
	cannedvvtTable1LoadBins();
	cannedvvtTable1();
	cannedvvtTable2RpmBins();
	cannedvvtTable2LoadBins();
	cannedvvtTable2();
	cannedscriptTable1RpmBins();
	cannedscriptTable1LoadBins();
	cannedscriptTable2RpmBins();
	cannedscriptTable2LoadBins();
	cannedscriptTable3RpmBins();
	cannedscriptTable3LoadBins();
	cannedscriptTable3();
	cannedscriptTable4RpmBins();
	cannedscriptTable4LoadBins();
	cannedscriptTable4();
	cannedalsIgnRetardrpmBins();
	cannedalsIgnRetardLoadBins();
	cannedALSTimingRetardTable();
	cannedalsFuelAdjustmentrpmBins();
	cannedalsFuelAdjustmentLoadBins();
	cannedALSFuelAdjustment();
	cannedalsIgnSkiprpmBins();
	cannedalsIgnSkipLoadBins();
	cannedALSIgnSkipTable();
	cannedignitionRpmBins();
	cannedignitionLoadBins();
	cannedignitionTable();
	cannedignBlends1_rpmBins();
	cannedignBlends1_loadBins();
	cannedignBlends1_table();
	cannedignBlends2_rpmBins();
	cannedignBlends2_loadBins();
	cannedignBlends2_table();
	cannedignBlends3_table();
	cannedveBlends1_table();
	cannedveBlends2_loadBins();
	cannedveBlends2_table();
	cannedveBlends3_rpmBins();
	cannedveBlends3_loadBins();
	cannedveBlends3_table();
	cannedboostOpenLoopBlends1_rpmBins();
	cannedboostClosedLoopBlends1_table();
	cannedboostClosedLoopBlends2_rpmBins();
	cannedboostClosedLoopBlends2_loadBins();
	cannedboostClosedLoopBlends2_table();
	cannedignitionIatCorrTempBins();
	cannedignitionIatCorrLoadBins();
	cannedignitionIatCorrTable();
	cannedveRpmBins();
	cannedveLoadBins();
	cannedveTable();
	cannedfuelTrimRpmBins();
	cannedfuelTrimLoadBins();
	cannedfuelTrims1_table();
	cannedfuelTrims2_table();
	cannedfuelTrims3_table();
	cannedfuelTrims4_table();
	cannedfuelTrims5_table();
	cannedfuelTrims6_table();
	cannedfuelTrims7_table();
	cannedfuelTrims8_table();
	cannedfuelTrims9_table();
	cannedfuelTrims10_table();
	cannedfuelTrims11_table();
	cannedfuelTrims12_table();
	cannedignTrimRpmBins();
	cannedignTrimLoadBins();
	cannedignTrims1_table();
	cannedignTrims2_table();
	cannedignTrims3_table();
	cannedignTrims4_table();
	cannedignTrims5_table();
	cannedignTrims6_table();
	cannedignTrims7_table();
	cannedignTrims8_table();
	cannedignTrims9_table();
	cannedignTrims10_table();
	cannedignTrims11_table();
	cannedignTrims12_table();
	cannedinjPhaseRpmBins();
	cannedinjPhaseLoadBins();
	cannedinjectionPhase();
	cannedpedalToTpsRpmBins();
	cannedthrottle2TrimRpmBins();
	cannedthrottle2TrimTpsBins();
	cannedthrottle2TrimTable();
	cannedmaxKnockRetardRpmBins();
	cannedmaxKnockRetardLoadBins();
	cannedmaxKnockRetardTable();
	cannedlambdaRpmBins();
	cannedlambdaLoadBins();
	cannedlambdaTable();
	cannedgppwm4_table();
	cannedhpfpTargetRpmBins();
	cannedhpfpTargetLoadBins();
	cannedhpfpCompensationRpmBins();
	cannedhpfpCompensationLoadBins();
	cannedhpfpCompensation();
	cannedpostCrankingFactor();
```
