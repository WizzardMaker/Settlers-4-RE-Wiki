# CGfxManager

```cpp
struct __unaligned __declspec(align(1)) CGfxManager
{
  _DWORD *landscapeSceneVertexBufferEnd;
  
  LPDIRECTDRAW DirectDrawDevice;
  
  
  int Clipper1;
  _BYTE gap_C[12];
  int Clipper2;
  _BYTE gap_1C[12];
  
  int Direct3D7;
  
  int field_2C;
  DWORD *unknownClass;
  _BYTE gap_34[24];
  
  IDirectDraw7 *DirectDraw7;
  
  CSurfaceV7 *LandscapeSurface;
  int field_54;
  CSurfaceV7 *LandscapeSurface2;
  CSurfaceV7 *FinalRenderSurface;
  CSurfaceV7 *field_60;
  CSurfaceV7 *PrimarySurface;
  
  _BYTE field_68[176];
  int field_118;
  int field_11C;
  int field_120;
  int field_124;
  
  CSurface7 *MiniMapSurface;
  CSurfaceV7 *MiniMapAreaSurface;
  
  __int64 field_130;
  _BYTE gap_138[8];
  __int64 field_140;
  _BYTE gap_148[8];
  __int64 field_150;
  _BYTE gap_158[8];
  __int64 field_160;
  
  CSurfaceV7 *MoveCursorSurface;
  CSurfaceV7 *ZoomCursorSurface;
  
  _BYTE gap_170[720];
  int field_440;
  _DWORD field_444;
  _BYTE gap_448[716];
  __int16 EngineInitializedFlag;
  int field_716;
  _BYTE field_71A;
  _BYTE needsRefresh;
  int field_71C;
  int field_720;
  _DWORD Lockcounter;
  int field_728;
  int field_72C;
  _BYTE gap_730[4];
  int field_734;
  int field_738;
  int field_73C;
  int field_740;
  int field_744;
  int field_748;
  int field_74C;
  int field_750;
  int field_754;
  int field_758;
  int field_75C;
  char field_760;
  _BYTE gap_761[3];
  int field_764;
  int field_768;
  int field_76C;
  int field_770;
  int field_774;
  int field_778;
  int field_77C;
  int field_780;
  int field_784;
  char field_788;
};
```