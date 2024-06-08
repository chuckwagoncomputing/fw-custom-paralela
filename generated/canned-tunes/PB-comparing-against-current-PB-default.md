# PB-comparing-against-current-PB-default

// canned tune https://rusefi.com/online/view.php?msq=1626

```
    // default 227.0
    engineConfiguration->vvtOffsets[0] = 203;
    // default 50.0
    engineConfiguration->vvtOffsets[1] = 20;
    // default 1214.0
    engineConfiguration->injector.flow = 1000;
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
    engineConfiguration->benchTestOnTime = 1.5;
    // default "GPPWM Output 3"
    engineConfiguration->ignBlends[0].blendParameter = GPPWM_Zero;
    // default "VVT 1 I"
    engineConfiguration->ignBlends[0].yAxisOverride = GPPWM_Zero;
    // default "Aux Linear 1"
    engineConfiguration->veBlends[2].blendParameter = GPPWM_Zero;
    // default "IAT"
    engineConfiguration->boostOpenLoopBlends[0].blendParameter = GPPWM_Zero;
    // default "Aux Temp 2"
    engineConfiguration->boostClosedLoopBlends[1].blendParameter = GPPWM_Zero;
    // default "CLT"
    engineConfiguration->boostClosedLoopBlends[1].yAxisOverride = GPPWM_Zero;
    // default 0.34
    engineConfiguration->throttlePedalSecondaryUpVoltage = 0.74;
    // default 1.86
    engineConfiguration->throttlePedalSecondaryWOTVoltage = 2.28;
    // default "Normal"
    engineConfiguration->clutchDownPinInverted = false;
    // default "Normal"
    engineConfiguration->clutchUpPinInverted = false;
    // default "Normal"
    engineConfiguration->flexSensorInverted = false;
    // default 0.05
    engineConfiguration->idleRpmPid.pFactor = 0.03;
    // default 0.0
    engineConfiguration->idle_derivativeFilterLoss = 0.1;
    // default 0.0
    engineConfiguration->idle_antiwindupFreq = 0.1;
    // default 0.0
    engineConfiguration->idleRpmPid.dFactor = 5.0E-4;
    // default 50.0
    engineConfiguration->idlePidRpmDeadZone = 40;
    // default "false"
    engineConfiguration->useSeparateAdvanceForIdle = true;
    // default "Open Loop"
    engineConfiguration->idleMode = IM_AUTO;
    // default "false"
    engineConfiguration->useIdleTimingPidControl = true;
    // default 0.0
    engineConfiguration->idleTimingPid.dFactor = 5.0E-4;
    // default 0.0
    engineConfiguration->idleTimingSoftEntryTime = 1;
    // default 88.0
    engineConfiguration->fanOffTemperature = 86;
    // default "false"
    engineConfiguration->enableFan1WithAc = true;
    // default "false"
    engineConfiguration->disableFan1WhenStopped = true;
    // default 91.0
    engineConfiguration->fan2OffTemperature = 90;
    // default "false"
    engineConfiguration->enableFan2WithAc = true;
    // default "false"
    engineConfiguration->disableFan2WhenStopped = true;
    // default 4.0
    engineConfiguration->startUpFuelPumpDuration = 2;
    // default 0.0
    engineConfiguration->knockBandCustom = 14.8;
    // default 87.5
    engineConfiguration->cylinderBore = 77;
    // default "false"
    engineConfiguration->fuelClosedLoopCorrectionEnabled = true;
    // default 60.0
    engineConfiguration->stft.startupDelay = 30;
    // default 60.0
    engineConfiguration->stft.minClt = 40;
    // default 12.0
    engineConfiguration->stft.minAfr = 10;
    // default 1500.0
    engineConfiguration->vvtControlMinRpm = 550;
    // default "advance"
    engineConfiguration->invertVvtControlExhaust = retard;
    // default 0.0
    engineConfiguration->auxPid[0].dFactor = 5.0E-4;
    // default 0.0
    engineConfiguration->auxPid[1].offset = 33;
    // default 0.0
    engineConfiguration->auxPid[1].pFactor = 1;
    // default 0.0
    engineConfiguration->auxPid[1].iFactor = 0.005;
    // default 0.0
    engineConfiguration->auxPid[1].dFactor = 5.0E-4;
    // default 5.0
    engineConfiguration->totalGearsCount = 6;
    // default 12.0
    engineConfiguration->gearRatio[0] = 8.1;
    // default 6.0
    engineConfiguration->gearRatio[1] = 4.3;
    // default 4.4
    engineConfiguration->gearRatio[2] = 2.9;
    // default 2.4
    engineConfiguration->gearRatio[3] = 2.3;
    // default 1.0
    engineConfiguration->gearRatio[4] = 1.88;
    // default 0.0
    engineConfiguration->gearRatio[5] = 1.57;
    // default 200.0
    engineConfiguration->afterCrankingIACtaperDuration = 100;
    // default "Launch Button"
    engineConfiguration->launchActivationMode = CLUTCH_INPUT_LAUNCH;
    // default "NONE"
    engineConfiguration->hpfpCam = HPFP_CAM_EX1;
    // default 10.0
    engineConfiguration->hpfpPeakPos = -30;


	pbcannedknockNoiseRpmBins();
	pbcannedknockBaseNoise();
	pbcanneddwellVoltageCorrVoltBins();
	pbcanneddwellVoltageCorrValues();
	pbcannedtpsTspCorrValuesBins();
	pbcannedtpsTspCorrValues();
	pbcannedmafDecodingBins();
	pbcannedmafDecoding();
	pbcannediatFuelCorrBins();
	pbcannediatFuelCorr();
	pbcannedcltTimingBins();
	pbcannedcltTimingExtra();
	pbcannedcltFuelCorrBins();
	pbcannedcltFuelCorr();
	pbcannedcrankingFuelBins();
	pbcannedcrankingFuelCoef();
	pbcannedcrankingFuelCoefE100();
	pbcannedcltRevLimitRpmBins();
	pbcannedcltRevLimitRpm();
	pbcannedcltIdleCorrBins();
	pbcannedcltIdleCorr();
	pbcannedcltIdleRpm();
	pbcannedidleAdvanceBins();
	pbcannedidleAdvance();
	pbcannedfuelLevelBins();
	pbcannedfuelLevelValues();
	pbcannedhpfpLobeProfileQuantityBins();
	pbcannedhpfpLobeProfileAngle();
	pbcannedhpfpDeadtimeVoltsBins();
	pbcannedwwCltBins();
	pbcannedwwTauCltValues();
	pbcannedwwMapBins();
	pbcannedwwTauMapValues();
	pbcannedwwBetaCltValues();
	pbcannedwwBetaMapValues();
	pbcannedtcu_tccTpsBins();
	pbcannedtcu_tccLockSpeed();
	pbcannedtcu_tccUnlockSpeed();
	pbcannedtcu_pcAirmassBins();
	pbcannedtcu_pcValsR();
	pbcannedtcu_pcValsN();
	pbcannedtcu_pcVals1();
	pbcannedtcu_pcVals2();
	pbcannedtcu_pcVals3();
	pbcannedtcu_pcVals4();
	pbcannedtcu_pcVals12();
	pbcannedtcu_pcVals23();
	pbcannedtcu_pcVals34();
	pbcannedtcu_pcVals21();
	pbcannedtcu_pcVals32();
	pbcannedtcu_pcVals43();
	pbcannedtcu_32SpeedBins();
	pbcannedtcu_32Vals();
	pbcannedtcu_rangeM();
	pbcannedtcu_rangeM3();
	pbcannedtcu_rangeM2();
	pbcannedtcu_rangeM1();
	pbcannedignBlends1_blendBins();
	pbcannedignBlends1_blendValues();
	pbcannedignBlends2_blendBins();
	pbcannedignBlends2_blendValues();
	pbcannedignBlends3_blendBins();
	pbcannedignBlends3_blendValues();
	pbcannedignBlends4_blendBins();
	pbcannedignBlends4_blendValues();
	pbcannedveBlends1_blendBins();
	pbcannedveBlends1_blendValues();
	pbcannedveBlends2_blendBins();
	pbcannedveBlends2_blendValues();
	pbcannedveBlends3_blendBins();
	pbcannedveBlends3_blendValues();
	pbcannedveBlends4_blendBins();
	pbcannedveBlends4_blendValues();
	pbcannedboostOpenLoopBlends1_blendBins();
	pbcannedboostClosedLoopBlends2_blendBins();
	pbcannedthrottleEstimateEffectiveAreaBins();
	pbcannedtpsTpsAccelFromRpmBins();
	pbcannedtpsTpsAccelToRpmBins();
	pbcannedtpsTpsAccelTable();
	pbcannedtractionControlSlipBins();
	pbcannedvvtTable1RpmBins();
	pbcannedvvtTable1LoadBins();
	pbcannedvvtTable1();
	pbcannedvvtTable2RpmBins();
	pbcannedvvtTable2LoadBins();
	pbcannedvvtTable2();
	pbcannedscriptTable1RpmBins();
	pbcannedscriptTable1LoadBins();
	pbcannedscriptTable2RpmBins();
	pbcannedscriptTable2LoadBins();
	pbcannedscriptTable3RpmBins();
	pbcannedscriptTable3LoadBins();
	pbcannedscriptTable3();
	pbcannedscriptTable4RpmBins();
	pbcannedscriptTable4LoadBins();
	pbcannedscriptTable4();
	pbcannedalsIgnRetardrpmBins();
	pbcannedalsIgnRetardLoadBins();
	pbcannedALSTimingRetardTable();
	pbcannedalsFuelAdjustmentrpmBins();
	pbcannedalsFuelAdjustmentLoadBins();
	pbcannedALSFuelAdjustment();
	pbcannedalsIgnSkiprpmBins();
	pbcannedalsIgnSkipLoadBins();
	pbcannedALSIgnSkipTable();
	pbcannedignitionRpmBins();
	pbcannedignitionLoadBins();
	pbcannedignitionTable();
	pbcannedignBlends1_rpmBins();
	pbcannedignBlends1_loadBins();
	pbcannedignBlends1_table();
	pbcannedignBlends2_rpmBins();
	pbcannedignBlends2_loadBins();
	pbcannedignBlends2_table();
	pbcannedignBlends3_rpmBins();
	pbcannedignBlends3_loadBins();
	pbcannedignBlends3_table();
	pbcannedignBlends4_rpmBins();
	pbcannedignBlends4_loadBins();
	pbcannedveBlends1_rpmBins();
	pbcannedveBlends1_loadBins();
	pbcannedveBlends1_table();
	pbcannedveBlends2_rpmBins();
	pbcannedveBlends2_loadBins();
	pbcannedveBlends2_table();
	pbcannedveBlends3_rpmBins();
	pbcannedveBlends3_loadBins();
	pbcannedveBlends3_table();
	pbcannedveBlends4_rpmBins();
	pbcannedveBlends4_loadBins();
	pbcannedboostOpenLoopBlends1_rpmBins();
	pbcannedboostClosedLoopBlends1_table();
	pbcannedboostClosedLoopBlends2_rpmBins();
	pbcannedboostClosedLoopBlends2_loadBins();
	pbcannedboostClosedLoopBlends2_table();
	pbcannedignitionIatCorrTempBins();
	pbcannedignitionIatCorrLoadBins();
	pbcannedignitionIatCorrTable();
	pbcannedveRpmBins();
	pbcannedveLoadBins();
	pbcannedveTable();
	pbcannedfuelTrimRpmBins();
	pbcannedfuelTrimLoadBins();
	pbcannedfuelTrims1_table();
	pbcannedfuelTrims2_table();
	pbcannedfuelTrims3_table();
	pbcannedfuelTrims4_table();
	pbcannedfuelTrims5_table();
	pbcannedfuelTrims6_table();
	pbcannedfuelTrims7_table();
	pbcannedfuelTrims8_table();
	pbcannedfuelTrims9_table();
	pbcannedfuelTrims10_table();
	pbcannedfuelTrims11_table();
	pbcannedfuelTrims12_table();
	pbcannedignTrimRpmBins();
	pbcannedignTrimLoadBins();
	pbcannedignTrims1_table();
	pbcannedignTrims2_table();
	pbcannedignTrims3_table();
	pbcannedignTrims4_table();
	pbcannedignTrims5_table();
	pbcannedignTrims6_table();
	pbcannedignTrims7_table();
	pbcannedignTrims8_table();
	pbcannedignTrims9_table();
	pbcannedignTrims10_table();
	pbcannedignTrims11_table();
	pbcannedignTrims12_table();
	pbcannedmapEstimateRpmBins();
	pbcannedmapEstimateTpsBins();
	pbcannedmapEstimateTable();
	pbcannedinjPhaseRpmBins();
	pbcannedinjPhaseLoadBins();
	pbcannedinjectionPhase();
	pbcannedthrottle2TrimRpmBins();
	pbcannedthrottle2TrimTpsBins();
	pbcannedthrottle2TrimTable();
	pbcannedmaxKnockRetardRpmBins();
	pbcannedmaxKnockRetardLoadBins();
	pbcannedmaxKnockRetardTable();
	pbcannedlambdaRpmBins();
	pbcannedlambdaLoadBins();
	pbcannedlambdaTable();
	pbcannedinjectorStagingRpmBins();
	pbcannedinjectorStagingLoadBins();
	pbcannedinjectorStagingTable();
	pbcannedhpfpTargetRpmBins();
	pbcannedhpfpTargetLoadBins();
	pbcannedhpfpCompensationRpmBins();
	pbcannedhpfpCompensationLoadBins();
	pbcannedhpfpCompensation();
	pbcannedcrankingCycleBins();
```
