# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': 'e61d7bb3006f451968714e2f653412081871e1ee',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': '5d4562d56eb3cc8ac23f70fd48e549d0751b2fde',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': '50bc4debdc3eec5045edbeb8ce164090e29b91f3',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': '42b315c15b1ff941b46bb3949c105e5386be8717',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'd91597a82f881d473887b560a03a7edf2720b72c',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': '1a337fe32d4d5be2ec2af7e02647005aeb358faa',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': 'c9a5acda16dc2759457dc856b5d7df00ac5bf4a2',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'bfd85956e1b4c1c79842ce857fc7fb15adb8a573',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'cbb4ab171fc7cd0b636a76ee542e238a8734f4be',
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
