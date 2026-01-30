# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '43023b117abb3153e2ca400010d51dabebaae446',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '732b82663601cce1df89f294225be0569200ae38',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '04f10f650d514df88b76d25e83db360142c7b174',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'd4671f690ac42f196795272114daadc5088967ce',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': '3cfca3829608e778cf59b0dab55d77f4f6c79bee',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '11aa53eab96b546c7fce5f5cb29e33069eeb9e9b',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '48a4bcbdf619e57204783f8c1a04c76c160ddd5b',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'a663eca87ba71294dd4b74ba9d3e64a72d725453',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': '472d81b2cec0db337128a9b1aa08822b7a8faba8',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
