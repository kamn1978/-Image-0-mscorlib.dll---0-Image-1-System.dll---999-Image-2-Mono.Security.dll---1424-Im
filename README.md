// Image 0: mscorlib.dll - 0
// Image 1: System.dll - 999
// Image 2: Mono.Security.dll - 1424
// Image 3: System.Core.dll - 1547
// Image 4: UnityEngine.SharedInternalsModule.dll - 1597
// Image 5: UnityEngine.CoreModule.dll - 1623
// Image 6: UnityEngine.AudioModule.dll - 1935
// Image 7: UnityEngine.ImageConversionModule.dll - 1955
// Image 8: UnityEngine.TextRenderingModule.dll - 1957
// Image 9: UnityEngine.UnityWebRequestModule.dll - 1973
// Image 10: UnityEngine.WebModule.dll - 1986
// Image 11: UnityEngine.AnimationModule.dll - 2003
// Image 12: UnityEngine.GameCenterModule.dll - 2032
// Image 13: UnityEngine.IMGUIModule.dll - 2054
// Image 14: UnityEngine.InputModule.dll - 2092
// Image 15: UnityEngine.JSONSerializeModule.dll - 2099
// Image 16: UnityEngine.ParticleSystemModule.dll - 2101
// Image 17: UnityEngine.Physics2DModule.dll - 2110
// Image 18: UnityEngine.PhysicsModule.dll - 2118
// Image 19: UnityEngine.UIModule.dll - 2134
// Image 20: UnityEngine.UNETModule.dll - 2144
// Image 21: UnityEngine.UnityAnalyticsModule.dll - 2190
// Image 22: UnityEngine.UnityConnectModule.dll - 2195
// Image 23: UnityEngine.UnityWebRequestWWWModule.dll - 2201
// Image 24: UnityEngine.VRModule.dll - 2203
// Image 25: UnityEngine.dll - 2210
// Image 26: Purchasing.Common.dll - 2211
// Image 27: UnityStore.dll - 2220
// Image 28: Apple.dll - 2231
// Image 29: Boo.Lang.dll - 2235
// Image 30: ChannelPurchase.dll - 2254
// Image 31: FacebookStore.dll - 2266
// Image 32: Security.dll - 2269
// Image 33: Tizen.dll - 2293
// Image 34: UnityEngine.Purchasing.dll - 2297
// Image 35: UnityEngine.UI.dll - 2337
// Image 36: winrt.dll - 2524
// Image 37: Photon3Unity3D.dll - 2529
// Image 38: Stores.dll - 2601
// Image 39: System.Xml.dll - 2734
// Image 40: UnityScript.Lang.dll - 3045
// Image 41: ArabicSupport.dll - 3049
// Image 42: FastDecals.dll - 3057
// Image 43: UnityEngine.Advertisements.Android.dll - 3064
// Image 44: UnityEngine.StandardEvents.dll - 3088
// Image 45: UnityEngine.Analytics.dll - 3090
// Image 46: UnityEngine.Networking.dll - 3116
// Image 47: Assembly-CSharp-firstpass.dll - 3234
// Image 48: Assembly-UnityScript-firstpass.dll - 3959
// Image 49: Assembly-CSharp.dll - 4031
// Image 50: Assembly-UnityScript.dll - 6466 
// Namespace: 
internal class <Module> // TypeDefIndex: 0
{
} 
// Namespace: System
public class Object // TypeDefIndex: 1
{ 	// Methods 	public void .ctor(); // 0x12FDCE0 	public virtual bool Equals(object obj); // 0x130636C 	public static bool Equals(object objA, object objB); // 0x1306380 	protected override void Finalize(); // 0x13063C8 	public virtual int GetHashCode(); // 0x13063CC 	public Type GetType(); // 0x13063D8 	protected object MemberwiseClone(); // 0x1306354 	public virtual string ToString(); // 0x13063DC 	public static bool ReferenceEquals(object objA, object objB); // 0x1306410 	internal static int InternalGetHashCode(object o); // 0x13063D0
} 
// Namespace: System
public abstract class ValueType // TypeDefIndex: 2
{ 	// Methods 	protected void .ctor(); // 0x1B0531C 	private static bool InternalEquals(object o1, object o2, out object[] fields); // 0x1B05324 	internal static bool DefaultEquals(object o1, object o2); // 0x1B05334 	public override bool Equals(object obj); // 0x1B05444 	internal static int InternalGetHashCode(object o, out object[] fields); // 0x1B05450 	public override int GetHashCode(); // 0x1B0545C 	public override string ToString(); // 0x1B05548
} 
// Namespace: System
public abstract class Attribute : _Attribute // TypeDefIndex: 3
{ 	// Methods 	protected void .ctor(); // 0x1475D50 	public virtual object get_TypeId(); // 0x1475D58 	private static void CheckParameters(object element, Type attributeType); // 0x1475D60 	public static Attribute GetCustomAttribute(MemberInfo element, Type attributeType); // 0x1475F58 	public static Attribute GetCustomAttribute(MemberInfo element, Type attributeType, bool inherit); // 0x1475F74 	public override int GetHashCode(); // 0x1476024 	public virtual bool IsDefaultAttribute(); // 0x147602C 	public static bool IsDefined(ParameterInfo element, Type attributeType); // 0x1476034 	public static bool IsDefined(MemberInfo element, Type attributeType); // 0x14760D0 	public static bool IsDefined(MemberInfo element, Type attributeType, bool inherit); // 0x14760EC 	public static bool IsDefined(ParameterInfo element, Type attributeType, bool inherit); // 0x1476050 	public virtual bool Match(object obj); // 0x1476270 	public override bool Equals(object obj); // 0x1476280
} 
// Namespace: System.Runtime.InteropServices
public interface _Attribute // TypeDefIndex: 4
{
} 
// Namespace: System
public struct Int32 : IFormattable, IConvertible, IComparable, IComparable`1<int>, IEquatable`1<int> // TypeDefIndex: 5
{ 	// Fields 	public const int MaxValue = 2147483647; // 0x0 	public const int MinValue = -2147483648; // 0x0 	internal int m_value; // 0x8  	// Methods 	private bool System.IConvertible.ToBoolean(IFormatProvider provider); // 0x1652100 	private byte System.IConvertible.ToByte(IFormatProvider provider); // 0x1652190 	private char System.IConvertible.ToChar(IFormatProvider provider); // 0x1652220 	private DateTime System.IConvertible.ToDateTime(IFormatProvider provider); // 0x16522B8 	private Decimal System.IConvertible.ToDecimal(IFormatProvider provider); // 0x165235C 	private double System.IConvertible.ToDouble(IFormatProvider provider); // 0x16523F8 	private short System.IConvertible.ToInt16(IFormatProvider provider); // 0x1652488 	private int System.IConvertible.ToInt32(IFormatProvider provider); // 0x1652490 	private long System.IConvertible.ToInt64(IFormatProvider provider); // 0x1652520 	private sbyte System.IConvertible.ToSByte(IFormatProvider provider); // 0x16525B0 	private float System.IConvertible.ToSingle(IFormatProvider provider); // 0x1652640 	private object System.IConvertible.ToType(Type targetType, IFormatProvider provider); // 0x1652770 	private ushort System.IConvertible.ToUInt16(IFormatProvider provider); // 0x1652800 	private uint System.IConvertible.ToUInt32(IFormatProvider provider); // 0x1652890 	private ulong System.IConvertible.ToUInt64(IFormatProvider provider); // 0x1652920 	public int CompareTo(object value); // 0x1652A28 	public override bool Equals(object obj); // 0x1652AC4 	public override int GetHashCode(); // 0x1652AD4 	public int CompareTo(int value); // 0x1652AF8 	public bool Equals(int obj); // 0x1652B24 	internal static bool ProcessTrailingWhitespace(bool tryParse, string s, int position, Exception exc); // 0x1651B38 	internal static bool Parse(string s, bool tryParse, out int result, out Exception exc); // 0x1652B38 	public static int Parse(string s, IFormatProvider provider); // 0x1652E48 	public static int Parse(string s, NumberStyles style); // 0x1652E6C 	internal static bool CheckStyle(NumberStyles style, bool tryParse, Exception exc); // 0x1652E88 	internal static bool JumpOverWhite(int pos, string s, bool reportError, bool tryParse, Exception exc); // 0x1652F94 	internal static void FindSign(int pos, string s, NumberFormatInfo nfi, bool foundSign, bool negative); // 0x16530D8 	internal static void FindCurrency(int pos, string s, NumberFormatInfo nfi, bool foundCurrency); // 0x165331C 	internal static bool FindExponent(int pos, string s, int exponent, bool tryParse, Exception exc); // 0x16534AC 	internal static bool FindOther(int pos, string s, string other); // 0x1653970 	internal static bool ValidDigit(char e, bool allowHex); // 0x1653AC4 	internal static Exception GetFormatException(); // 0x163A468 	internal static bool Parse(string s, NumberStyles style, IFormatProvider fp, bool tryParse, out int result, out Exception exc); // 0x1653BC0 	public static int Parse(string s); // 0x1654BEC 	public static int Parse(string s, NumberStyles style, IFormatProvider provider); // 0x1651D44 	public static bool TryParse(string s, out int result); // 0x163D830 	public static bool TryParse(string s, NumberStyles style, IFormatProvider provider, out int result); // 0x1654C8C 	public override string ToString(); // 0x1654CD0 	public string ToString(IFormatProvider provider); // 0x1654D68 	public string ToString(string format); // 0x1654E14 	public string ToString(string format, IFormatProvider provider); // 0x1654E20 	public TypeCode GetTypeCode(); // 0x1654E28
} 
// Namespace: System
public interface IFormattable // TypeDefIndex: 6
{ 	// Methods 	public abstract string ToString(string format, IFormatProvider formatProvider); // 0
} 
// Namespace: System
public interface IConvertible // TypeDefIndex: 7
{ 	// Methods 	public abstract bool ToBoolean(IFormatProvider provider); // 0 	public abstract byte ToByte(IFormatProvider provider); // 0 	public abstract char ToChar(IFormatProvider provider); // 0 	public abstract DateTime ToDateTime(IFormatProvider provider); // 0 	public abstract Decimal ToDecimal(IFormatProvider provider); // 0 	public abstract double ToDouble(IFormatProvider provider); // 0 	public abstract short ToInt16(IFormatProvider provider); // 0 	public abstract int ToInt32(IFormatProvider provider); // 0 	public abstract long ToInt64(IFormatProvider provider); // 0 	public abstract sbyte ToSByte(IFormatProvider provider); // 0 	public abstract float ToSingle(IFormatProvider provider); // 0 	public abstract string ToString(IFormatProvider provider); // 0 	public abstract object ToType(Type conversionType, IFormatProvider provider); // 0 	public abstract ushort ToUInt16(IFormatProvider provider); // 0 	public abstract uint ToUInt32(IFormatProvider provider); // 0 	public abstract ulong ToUInt64(IFormatProvider provider); // 0
} 
// Namespace: System
public interface IComparable // TypeDefIndex: 8
{ 	// Methods 	public abstract int CompareTo(object obj); // 0
} 
// Namespace: System
public interface IComparable`1 // TypeDefIndex: 9
{ 	// Methods 	public abstract int CompareTo(T other); // 0
} 
// Namespace: System
public sealed class SerializableAttribute : Attribute // TypeDefIndex: 10
{ 	// Methods 	public void .ctor(); // 0x11D4CA4
} 
// Namespace: System
public sealed class AttributeUsageAttribute : Attribute // TypeDefIndex: 11
{ 	// Fields 	private AttributeTargets valid_on; // 0x8 	private bool allow_multiple; // 0xC 	private bool inherited; // 0xD  	// Methods 	public void .ctor(AttributeTargets validOn); // 0x1476328 	public bool get_AllowMultiple(); // 0x1476354 	public void set_AllowMultiple(bool value); // 0x147635C 	public bool get_Inherited(); // 0x1476364 	public void set_Inherited(bool value); // 0x147636C
} 
// Namespace: System.Runtime.InteropServices
public sealed class ComVisibleAttribute : Attribute // TypeDefIndex: 12
{ 	// Fields 	private bool Visible; // 0x8  	// Methods 	public void .ctor(bool visibility); // 0xF5C718
} 
// Namespace: System
public interface IEquatable`1 // TypeDefIndex: 13
{ 	// Methods 	public abstract bool Equals(T other); // 0
} 
// Namespace: System
public struct Int64 : IFormattable, IConvertible, IComparable, IComparable`1<long>, IEquatable`1<long> // TypeDefIndex: 14
{ 	// Fields 	public const long MaxValue = 9223372036854775807; // 0x0 	public const long MinValue = -9223372036854775808; // 0x0 	internal long m_value; // 0x8  	// Methods 	private bool System.IConvertible.ToBoolean(IFormatProvider provider); // 0x15A1BBC 	private byte System.IConvertible.ToByte(IFormatProvider provider); // 0x15A1C58 	private char System.IConvertible.ToChar(IFormatProvider provider); // 0x15A1CF4 	private DateTime System.IConvertible.ToDateTime(IFormatProvider provider); // 0x15A1D98 	private Decimal System.IConvertible.ToDecimal(IFormatProvider provider); // 0x15A1E48 	private double System.IConvertible.ToDouble(IFormatProvider provider); // 0x15A1EF0 	private short System.IConvertible.ToInt16(IFormatProvider provider); // 0x15A1F8C 	private int System.IConvertible.ToInt32(IFormatProvider provider); // 0x15A2028 	private long System.IConvertible.ToInt64(IFormatProvider provider); // 0x15A20C4 	private sbyte System.IConvertible.ToSByte(IFormatProvider provider); // 0x15A2160 	private float System.IConvertible.ToSingle(IFormatProvider provider); // 0x15A21FC 	private object System.IConvertible.ToType(Type targetType, IFormatProvider provider); // 0x15A2330 	private ushort System.IConvertible.ToUInt16(
